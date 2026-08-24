# ExtraBar updates

This repository publishes ExtraBar's production Sparkle feed at
`https://appitstudio.github.io/extra-bar-updates/appcast.xml`.

## Append-only release history

`appcast.xml` is append-only: add each new `<item>` above the existing items and
never remove an older release. Update-window licensing compares each item's
`pubDate` with the customer's server-issued update expiry, so every item must
carry the real release timestamp. Never guess or backdate a release.

The retained 1.0–1.5.2 history was reconstructed from each version's committed
production appcast. Duplicate commits for 1.0 and 1.1.3 were collapsed because
they described the same release. Four malformed weekday labels were corrected
without changing their recorded calendar dates, times, or timezones: 1.2.9,
1.3.0, 1.3.1, and 1.3.2. Version 1.5.1 was not present in the repository's
stable production appcast history (it was a beta prerelease) and was not added.

The committed metadata for 1.0 through 1.2.0 is verified, but those historical
items used the mutable `releases/download/prod/ExtraBar.dmg` URL and no immutable
version tags/assets exist for them. Their recorded URLs were retained rather
than guessing replacements. Immutable per-version release assets begin at
1.2.1; every future item must also use an immutable version-specific asset.

Before committing a feed change, run:

```bash
python3 scripts/sync_keyper_releases.py --appcast appcast.xml --validate-only
xmllint --noout appcast.xml
```

## Keyper release registration

The GitHub Actions workflow validates pull requests. After `appcast.xml` changes
on `main`, it idempotently posts every retained version and `pubDate` to Keyper's
`/api/releases` endpoint. It can also be run manually to perform the initial
history backfill.

Repository configuration required before the first registration:

- Secret `KEYPER_RELEASE_TOKEN`: the dedicated Keyper write token bound to
  ExtraBar's `stable` release track. Never use the API key shipped in ExtraBar.
- Optional variable `KEYPER_RELEASE_ENDPOINT`: override for the complete HTTPS
  endpoint. It defaults to `https://keyper.appitstudio.com/api/releases`.

The workflow has read-only repository permissions and never prints the token.
