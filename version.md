VERSION: 1.2.1
DETAILS:

This is technical release notes for ExtraBar 1.2.1.
Convert it to be more user-friendly and concise.

## Shiori Bookmark Manager Integration

ExtraBar now integrates with **Shiori**, a powerful bookmark manager, bringing your entire bookmark library directly into your menu bar. Browse, search, organize, and manage bookmarks without leaving your workflow.

---

### Bookmark Widget

- **Bar widget** — Add a Shiori bookmark widget to your bar for instant access to your bookmarks from the menu bar.
- **Search & filter** — Search bookmarks by keyword, filter by folder or tags, all within the widget popover.
- **Folder navigation** — Browse bookmark folders with full subfolder navigation using arrow keys.
- **Quick Add** — Add a new bookmark directly from the widget with `Cmd +` keyboard shortcut.
- **Edit & delete** — Edit bookmark details or delete bookmarks inline from the widget.
- **Copy URL** — One-click copy of any bookmark URL to clipboard with visual confirmation.
- **Theme switcher** — Toggle between System, Light, and Dark appearance for the bookmark popover.
- **Freshness indicator** — See at a glance whether your bookmarks are fresh from the server, cached, or offline.
- **Keyboard navigation** — Full keyboard support for navigating folders and bookmark lists.

### Bookmark Manager Window

A dedicated full-featured Bookmark Manager for organizing your library:

- **Bookmarks** — View all bookmarks with search, folder/tag filters, and pagination.
- **Folders** — Create, edit, rename, and delete folders with hierarchical subfolder support.
- **Tags** — Manage tags with color coding for visual organization.
- **Bulk operations** — Multi-select mode for bulk deleting bookmarks, tags, and folders.
- **Batch move** — Move multiple bookmarks to a folder in one action.
- **Sync fix** — Identify and resolve out-of-sync bookmarks with dedicated fix actions.
- **Styled bookmark cards** — Each bookmark row features a colored accent border, favicon, tags, and hover actions (edit, copy, delete).

### Import & Export

- **Import** from multiple sources:
  - Browser HTML bookmark exports
  - JSON files
  - Raindrop.io exports
  - Pocket exports
  - Pinboard exports
- **Export** your bookmarks to:
  - JSON
  - CSV
  - HTML (browser-compatible)
- Import progress tracking with status polling.

### Authentication & Accounts

- **Keyper authentication** — Sign in with your Keyper account for streamlined registration and login.
- **Deep link login** — Authenticate from the Shiori website directly into ExtraBar via `extrabar://` URL scheme.
- **Subscription management** — View your current plan (Free / Pro / Plus (Soon)), usage limits, and upgrade options.
- **Web-based checkout** — One-click upgrade to Pro or Plus (Soon) plans
- **Checkout callbacks** — Automatic subscription sync.
- **Persistent sessions** — Stay signed in across app restarts with secure Keychain token storage.

### Offline & Sync

- **Online-first caching** — Bookmarks load instantly from local cache, then refresh from the server in the background.
- **Offline mode** — Full access to cached bookmarks when the network is unavailable.
- **Background sync** — Automatic synchronization with configurable intervals and network reconnect detection.
- **Pending changes** — Offline edits are preserved and synced when connectivity is restored.

### Data & Storage

- **CoreData cache layer** — Local cache for bookmarks, folders, and tags with fast search.
- **Favicon caching** — Website favicons are cached locally for fast rendering.
- **Device-scoped bookmarks** — Support for device-specific and shared bookmark visibility.

### Settings

- **Shiori section** in Settings for managing your account, viewing subscription details, and configuring the integration.
- **Bookmark Manager** accessible from Settings or directly from the app menu.

---

### Other Improvements

- Added Bookmark Manager menu item to the application menu for quick access.
- Improved keyboard navigation focus handling in bar content.
- Enhanced popover handling for bookmark widgets in bar and menu bar modes.

---
