VERSION: 1.2.3
DETAILS:

This is technical release notes for ExtraBar
Convert it to be more user-friendly and concise.

ExtraBar v1.2.3 — Release Notes

New Features

Keyboard Shortcut Action Type — New menu action type that simulates keyboard shortcuts via CGEvent. Configure any key + modifier combination (Cmd, Shift, Opt, Ctrl, Fn) and send it to the previously focused app. "Restore App Focus" returns focus to your app before sending keys so shortcuts act on the correct context.
Move/Copy Items Between Presets & Folders — Batch move or copy items between presets and folder widgets. Multi-select mode with Select All, action bar, and context menu support.
Global Hotkey for Shiori Bookmark Manager — Open the Bookmark Manager with Shift+Cmd+B. Configurable shortcut in Settings.
Keyboard Navigation in Tag/Folder Pickers — Arrow key navigation with highlighted state in bookmark tag and folder pickers. Return/Space opens pickers when focused.
Auto-Save Indicator — Replaced manual Save buttons with a subtle inline saving/saved status indicator on screens that already auto-save.
Clickable List Rows — Clicking anywhere on a preset, app/widget, or action row now opens its settings, matching the cog icon behavior.
Improvements

Folder Widget Settings Redesign — Revamped folder widget settings with inlined header (Name, Icon, Color) and dedicated screen for item selection instead of popup. Add action now opens the action library directly.
Consolidated Widget Editor UI — New CompactNameIconColorRow component streamlines name, icon, and color fields across Action, Folder, and Bookmark widget editors.
Inline Action Parameters — Action parameters are now shown inline in folder widget and batch creation flows instead of a separate popup.
Bookmark Widget Polish — Anchored window for menu-mode bookmark widget, rounded neutral chrome, and improved popover anchor positioning.
Responsive Widget Editor Layout — Widget editor uses flexible max-width/max-height for better adaptation to various screen sizes.
Bug Fixes

Fixed preset item list not updating after removing an app — The Combine publisher handler was reading the old value during willSet; now correctly uses the new value from the publisher.
Fixed bookmark widget popover anchor in menu mode — Popover now anchors correctly when using menu bar mode.
Renamed sync status label from "Fresh" to "Sync" for clarity.
