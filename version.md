VERSION: 1.4.2
DETAILS:

new: Hide from Screen Capture — a Privacy toggle in Settings → General that excludes the floating bar and its bookmark popovers/panels from screenshots, screen recordings, and screen sharing (Zoom, QuickTime, ScreenCaptureKit); menu bar icons are unaffected, and turning it off recreates the bar windows so they become capturable again
new: Toggle Notch Mode now has a row in Hotkeys settings — it was registered globally on ⌥⌘N but had no way to change or remove it
new: Toggle Collapse Mode shows "Unavailable while Single Menu Merge is on" instead of silently doing nothing when it's inert
improved: Toggle Position default is now ⌥⌘P (was ⌥⌘M) — macOS reserves ⌥⌘M system-wide so the recorder rejected it and the hotkey never reached the app; already-recorded custom shortcuts are untouched
improved: The default menu bar icon renders as a template image with a transparent background, so it picks up correct contrast in light and dark menu bars instead of showing an opaque colored tile
bug fix: The menu bar icon's position (set by ⌘-dragging) now persists across relaunches
bug fix: ⌘, opens Settings
bug fix: Reset Defaults in Hotkeys settings now actually restores the shortcut defaults — previously it only reset the timing/indicator options
bug fix: The menu bar icon preview in Appearance no longer mutates the shared cached icon image
