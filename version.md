VERSION: 1.2.5
DETAILS:

New Features

ExtraBar Release Notes — March 2026

  New Features

  Unified Icon Picker
  - Replaced the old custom icon picker with a new unified icon libary picker sheet (Library, SF Symbols, App
   Icons, From URL)
  - Available across bar items, widgets, and folder items — consistent icon customization everywhere
  - SF Symbol categories fixed for proper browsing
  - Widgets now support custom icon overrides (SF Symbols, app icons, library icons, URL icons) with new
  customIconName, customIconColor, and customIconId properties on widget models
  - Custom icons render correctly in both the floating bar and menu bar inline mode

  Action Deep Links
  - New deep link system for executing actions directly via URL scheme (extrabar://action/...)
  - Supports 4 action kinds: menu actions, action widgets, folder widget actions, and folder widget app menu
   actions
  - Copy Deep Link button added to menu configuration, folder widget editors, and widget app menu editors —
  easily share or automate any action

  Bug Fixes & Improvements

  - Fixed SF Symbol category filtering in the symbol picker
  - Code cleanup and optimizations
