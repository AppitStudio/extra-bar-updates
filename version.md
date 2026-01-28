VERSION: 1.2.1
DETAILS:
  Run Script Action - Major Enhancements
  - Inline script support: Write and execute scripts directly without needing external files
  - Script output window: New toggle to show real-time script output in a dedicated window with async streaming
  - Shell environment options: Choose how scripts load your shell profile:
    - Default (no profile loading)
    - zsh with login profile (.zprofile/.zlogin)
    - zsh interactive (.zshrc)
    - bash with login profile (.bash_profile/.profile)
  - Improved script editor UI: Better parameters form with validation and multi-action creation support
  - Script language selection: Support for multiple scripting languages with appropriate syntax highlighting

  Menu Bar Inline Mode Improvements

  - Faster tooltip display: Reimplemented per-item popovers for immediate tooltip response during keyboard navigation
  - Improved popover management: Eliminated delays when navigating between items

  Bug Fixes

  - Fixed dual-mode visibility after wake: Bar no longer shows in both floating and inline modes after system sleep
  - Fixed tooltip persistence issue: Tooltips now properly clean up when system enters sleep
  - Status items restore correctly: Menu bar items properly restore after system wake

  ---
