VERSION: 1.5.0
DETAILS:

new: Connect an AI assistant — Claude, Cursor, VS Code, and Raycast can set up your ExtraBar for you; describe what you want ("add my daily apps," "build me a Figma menu") and it happens
new: One-click setup for every supported AI client from Settings → AI Assistant — install the Claude Desktop extension, copy the Claude Code command, or add ExtraBar to Cursor, VS Code, or Raycast in under a minute
new: Five guided setups ship out of the box — quick-start onboarding, a projects bar wired to your editor and terminal, a script-tool builder, Figma deep links, and a bar-organizing cleanup pass
new: Assistants can reorganize a whole menu in one go — alphabetize it (dividers stay put as section boundaries), move a single entry, or clean out several entries at once
new: Every AI-made change is safe by default — scripts, API calls, and keyboard shortcuts an assistant creates are held as "(Approval Required)" until you review the exact script, URL, or keys and approve them yourself
new: Deleting anything — a preset, an item, a menu entry — always asks first, with an option to allow deletions for the rest of your session
new: "Revert Last AI Change" in Settings → AI Assistant undoes the assistant's most recent edit in one click, restoring the affected preset to how it was before
new: A local audit log tracks everything an AI assistant does to your bar, viewable in the AI Assistant settings pane under Recent AI Changes
improved: The AI connection is entirely local to your Mac — no data about your bar setup is ever sent off your device
improved: Bar position and appearance are now app-wide settings instead of being baked into each preset; switching presets changes your items and menus without moving your bar or changing its colours, and the "Include appearance settings" checkbox is gone from the new-preset sheet
bug fix: Fixed drag-to-reorder being inert in the folder and widget menu editors — the handles now actually move rows
bug fix: Fixed your bar jumping back to an old position or background colour when you switched presets
bug fix: Fixed a crash when running a script action that finished very quickly
bug fix: Script output that uses Windows-style line endings now shows up as proper separate lines
bug fix: Fixed missing actions in the Maps, Photos, Reminders, and Shortcuts presets, plus "Open in Terminal" in the folder preset — they were being silently dropped
bug fix: Custom icon tint colours now stick when you edit an existing item
