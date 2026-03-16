VERSION: 1.2.6
DETAILS:

⚙️ settings: Renamed "Display Modes" to "Position" with visual mode picker cards — tap to select Menu Bar or Floating Bar instead of the old toggle.
⚙️ settings: Renamed "Menu Mode" to "Collapse Mode" across the entire app.
⚙️ settings: Removed the Accessibility settings page — Bar Size and Icon Labels now live under Appearance.
⚙️ settings: Moved Dock Icon and Menu Bar Icon pickers from Appearance to General.
⚙️ settings: Merged three hotkey sections (Bar Control, Mode Control, Shiori) into one flat "Shortcuts" list.
⚙️ settings: Removed duplicate Shiori shortcut recorder from the Shiori settings page.
⚙️ settings: Renamed "Toggle Bar" to "Show / Hide Bar".
⚙️ settings: Collapse Mode navigation picker changed from a toggle to a segmented control.

🎨 ux: Removed redundant subtitles and descriptions across all settings.
🎨 ux: Replaced vague "items" with specific terms — "apps", "icons" etc.
🎨 ux: All settings now use solid opaque backgrounds instead of translucent blur.
🎨 ux: Standardized all back buttons to use the same style and position.
🎨 ux: Fixed inconsistent button animations when entering/exiting multi-select mode.
🎨 ux: Footer buttons changed from icon+text to icon-only with tooltips.
🎨 ux: Simplified the Accessibility permission popover.
🎨 ux: Removed keyboard navigation reference guide from Hotkeys and footer.

⚡ improved: App icons now load in high resolution, avoiding macOS Tahoe's padded app icon rendering.
⚡ improved: SF Symbols in the floating bar now render at high resolution.
⚡ improved: Collapse Mode menu icons now scale with bar size.
⚡ improved: Transparent mode now produces a truly invisible bar — hooray for minimalism.
⚡ improved: Menu bar icons bumped from 18pt to 22pt to match native macOS status item size.
⚡ improved: Fixed flash when navigating back from the action editor.