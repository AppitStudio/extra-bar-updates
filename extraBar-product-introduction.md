# ExtraBar - Product Introduction & Marketing Content

> **Version:** Beta 1.0
> **Platform:** macOS 12.4+
> **Built for:** Power users who want more control over their workflow

---

## Tagline Options

**Primary:**
> "Your Mac. Your Rules. Your Bar."

**Alternatives:**
- "Customize your workflow, one click at a time."
- "The menu bar that works the way you think."
- "Power at a glance. Actions in a click."
- "Beyond shortcuts. Beyond limits."

---

## Hero Section Copy

### Headline
**Take Control of Your Mac Workflow**

### Subheadline
ExtraBar gives power users a customizable menu bar with instant access to apps, deep links, and custom actions—without the limitations of macOS's native menu bar.

### Value Proposition (One-liner)
ExtraBar is a customizable bar for macOS that lets you create your own menu items with deep links, quick actions, and app-specific shortcuts—placed exactly where you want them.

---

## The Problem

**The macOS menu bar has limitations:**

- **Space constraints** - Limited room for icons, especially on MacBooks with the notch
- **No custom actions** - You can only launch apps, not trigger specific actions within them
- **No deep linking** - Can't jump directly to a Zoom meeting, Slack channel, or Figma project
- **No project lists** - IDEs limit you to "recent items" instead of your full project library
- **One-size-fits-all** - Every app gets the same basic menu, regardless of how you use it

**Your workflow deserves better.**

---

## The Solution

ExtraBar is a fully customizable bar that gives you:

1. **Custom menu actions** for every app—not just "Open" and "Quit"
2. **Deep links** that jump straight into meetings, channels, playlists, and pages
3. **Two display modes** to fit your screen preferences
4. **Full keyboard navigation** for power users who hate the mouse
5. **Built-in presets** for 36+ popular apps—works out of the box

---

## How It Works

### Two Display Modes

**1. Floating Bar Mode (Default)**
A sleek, separate bar window positioned at the top of your screen, just below the native macOS menu bar.

- **Toggle visibility** with a customizable hotkey
- **Auto-hide on hover** - appears when you need it, hides when you don't
- **No space limitations** - add as many items as you need
- **Modern glass design** that blends with macOS

**2. Menu Bar Inline Mode**
Renders your ExtraBar items as native icons in the macOS system menu bar.

- **Zero extra screen space** - uses existing menu bar real estate
- **Native appearance** - looks like it belongs on your Mac
- **Toggle hide/show** - keep a clean bar until you need more
- **Full-color icons** - not the typical monochrome menu bar look

---

## Core Features

### Custom Menu Actions (16 Action Types)

Every item in ExtraBar can have a fully customized right-click menu with actions like:

| Action | What It Does |
|--------|--------------|
| **Open** | Launch or activate the app |
| **Quit / Force Quit** | Gracefully close or force-kill an app |
| **New Window** | Open a fresh window in the app |
| **Hide / Show** | Toggle app window visibility |
| **Show in Finder** | Reveal the app in Finder |
| **Copy Path** | Copy the app's file path to clipboard |
| **Open with...** | Open a file with a specific app |
| **Open in Terminal** | Launch a folder in Terminal |
| **Run Script** | Execute a shell script |
| **Run Shortcut** | Trigger a macOS Shortcut |
| **API Call** | Make an HTTP request |
| **Deep Link** | Open a URL scheme directly into an app |

### Deep Links - The Game Changer

ExtraBar's deep link system lets you jump directly into specific content within apps. No more navigating through menus.

**Pre-configured deep links for:**

| App | What You Can Do |
|-----|-----------------|
| **Zoom** | Join a meeting with one click (meeting ID + password) |
| **Slack** | Open specific channels or DM conversations |
| **Teams** | Start a chat with a specific person |
| **Discord** | Jump to servers and channels |
| **Notion** | Open specific pages instantly |
| **Obsidian** | Open notes or search your vault |
| **Spotify** | Play tracks, playlists, albums, or artist pages |
| **WhatsApp** | Send messages to specific contacts |

**Template-based URLs with parameters:**
```
zoommtg://zoom.us/join?confno={meetingId}&pwd={password}
spotify:playlist:{playlistId}
obsidian://open?vault={vaultName}&file={fileName}
```

### 36+ Built-in App Presets

ExtraBar comes with intelligent presets for popular apps. Right-click any supported app and get instant access to relevant actions.

**Categories:**

**Browsers:** Safari, Chrome
**Communication:** Zoom, Slack, Teams, Discord, WhatsApp
**Productivity:** Notion, Obsidian
**Creative:** Figma, Photoshop, Final Cut Pro
**Development:** VS Code, Xcode, Terminal, iTerm, Cursor, Zed, Nova, IntelliJ, PyCharm, WebStorm, Sublime Text
**Terminals:** Terminal, iTerm, Warp, Alacritty, Kitty, WezTerm, Ghostty, Hyper
**Media:** Spotify
**Microsoft Office:** Word, Excel, PowerPoint

### Full Keyboard Support

Navigate and trigger actions without touching your mouse:

- **Global hotkey** to show/hide the bar
- **Keyboard shortcuts** for every menu action
- **Quick navigation** between items

### Multi-Monitor Support

ExtraBar works seamlessly across multiple displays:

- **Stable display identification** - remembers which screen each bar belongs to
- **Automatic repositioning** when screens are connected/disconnected
- **Resolution-aware** - bars stay in the right place when resolution changes

---

## Use Cases

### For Meeting Warriors

**Problem:** You have 15 recurring Zoom meetings and waste time searching for meeting IDs.

**Solution:** Create a "Meetings" item with deep links to each room:
- Daily Standup → Join with one click
- 1:1 with Manager → Pre-filled meeting ID
- Team Retrospective → No more searching calendars

### For Developers

**Problem:** Your IDE's "Recent Projects" only shows 10 items, but you work on 30+ projects.

**Solution:** Add your IDE to ExtraBar with:
- Deep links to your most important project folders
- "Open Project..." action to browse any folder
- Pre-configured terminal sessions for common locations
- Quick "New Window" access

### For Designers

**Problem:** Jumping between Figma files requires navigating through the app every time.

**Solution:** Create deep links to your active projects:
- Design System → Opens directly to your component library
- Current Sprint → Jump to the active project file
- Client Presentations → One-click access

### For Power Users

**Problem:** You have complex workflows that require multiple clicks through app menus.

**Solution:** Create custom menu actions:
- Run shell scripts to automate tasks
- Trigger macOS Shortcuts from the menu bar
- Make API calls to integrate with web services
- Chain actions together for complex workflows

### For Music Lovers

**Problem:** Switching to your focus playlist requires opening Spotify and navigating.

**Solution:** Add Spotify with deep links:
- Focus Playlist → `spotify:playlist:your-focus-playlist-id`
- Favorite Album → `spotify:album:album-id`
- Artist Radio → Jump to discovery

---

## What Makes ExtraBar Different

### vs. Bartender / Ice / Hidden Bar

These apps **organize** your existing menu bar icons. ExtraBar **creates** new functionality.

| Feature | Bartender/Ice | ExtraBar |
|---------|---------------|----------|
| Hide/show icons | Yes | Yes (inline mode) |
| Custom actions | No | Yes - 16 action types |
| Deep links | No | Yes - template-based |
| App-specific menus | No | Yes - 36+ presets |
| Run scripts | No | Yes |
| Keyboard shortcuts | Limited | Full support |

### vs. Alfred / Raycast

These are **search-based launchers**. ExtraBar is **visual and persistent**.

| Feature | Alfred/Raycast | ExtraBar |
|---------|----------------|----------|
| Always visible | No | Yes |
| Mouse-friendly | No | Yes |
| Deep link templates | Limited | Yes - with parameters |
| Visual app bar | No | Yes |
| Right-click menus | No | Yes |

### vs. Native Dock

The Dock is great for launching apps. ExtraBar is great for **using** apps.

| Feature | macOS Dock | ExtraBar |
|---------|------------|----------|
| Launch apps | Yes | Yes |
| Custom right-click menus | No | Yes - fully customizable |
| Deep links | No | Yes |
| Toggle visibility | Limited | Yes - hotkey + auto-hide |
| Menu bar position | No | Yes |

---

## Key Benefits

### Save Time
- **One-click access** to meetings, projects, and content
- **No navigation** through app menus
- **Keyboard shortcuts** for everything

### Stay Focused
- **Auto-hide** keeps your screen clean
- **Instant access** when you need it
- **No context switching** between apps

### Work Your Way
- **Fully customizable** menus for every app
- **Two display modes** to match your preference
- **Presets** that work out of the box

### Built for macOS
- **Native performance** with Swift and SwiftUI
- **Modern design** with glass effects
- **Multi-monitor** support
- **Accessibility** built-in

---

## Technical Specifications

| Specification | Details |
|---------------|---------|
| **Platform** | macOS 12.4 (Monterey) or later |
| **Architecture** | Universal (Apple Silicon + Intel) |
| **Framework** | SwiftUI + AppKit hybrid |
| **Persistence** | CoreData (local storage) |
| **Action Types** | 16 built-in types |
| **App Presets** | 36+ popular apps |
| **Deep Link Apps** | 8+ with template support |

---

## Roadmap

### Current (Beta)
- Single bar architecture
- 16 action types
- 36+ app presets
- Deep link support
- Two display modes
- Keyboard navigation

### Planned
- System items (WiFi, battery, volume, Bluetooth)
- Widgets support
- Multiple bars
- iCloud sync
- Themes and presets
- Import/export configurations
- Plugin system for custom menus

---

## Pricing (Suggested Structure)

### Free Version
- Single bar with up to 10 items
- Basic action types (Open, Quit, Show in Finder)
- Menu bar inline mode

### Pro Version ($XX one-time or $XX/year)
- Unlimited items
- All 16 action types
- Deep links with templates
- All app presets
- Script execution
- Priority support

---

## Call-to-Action Options

**Primary CTA:**
> "Download ExtraBar Beta - Free"

**Secondary CTAs:**
- "See it in action" (demo video)
- "View all features"
- "Join the beta"

---

## Social Proof / Testimonials (Templates for future use)

> "ExtraBar completely changed how I navigate my Mac. One-click access to Zoom meetings? Game changer."
> — *[Beta User Name], Software Engineer*

> "Finally, a menu bar that does what I need. The deep links alone save me 30 minutes a day."
> — *[Beta User Name], Product Designer*

> "As a developer with 50+ projects, ExtraBar's custom IDE menus are exactly what I needed."
> — *[Beta User Name], Full Stack Developer*

---

## FAQ Content

**Q: How is ExtraBar different from Bartender?**
A: Bartender organizes existing menu bar icons. ExtraBar creates entirely new functionality—custom menus, deep links, scripts, and more.

**Q: Does ExtraBar replace my menu bar?**
A: No. ExtraBar adds a customizable bar alongside your native menu bar. You can choose to display it as a floating window or integrate items into your menu bar.

**Q: What apps have built-in presets?**
A: Over 36 apps including Zoom, Slack, VS Code, Figma, Spotify, Notion, Obsidian, and all major browsers, IDEs, and terminals.

**Q: Can I create my own menu actions?**
A: Yes. Every menu is fully customizable. Add, remove, and configure any of the 16 action types.

**Q: Does it work with multiple monitors?**
A: Yes. ExtraBar uses stable display identification to remember bar positions across monitor connections and resolution changes.

**Q: Is my data stored in the cloud?**
A: No. All data is stored locally using CoreData. iCloud sync is planned for a future release.

**Q: Does ExtraBar work in fullscreen apps?**
A: Yes. ExtraBar can overlay fullscreen applications using special window configuration.

---

## SEO Keywords

**Primary:** macOS menu bar app, Mac menu bar customization, custom menu bar Mac, productivity app Mac

**Long-tail:**
- macOS deep link launcher
- custom Mac menu bar actions
- Zoom meeting quick access Mac
- Mac app launcher power users
- IDE project launcher Mac
- Spotify deep links Mac menu bar
- macOS workflow automation

---

## Research Sources

This document was informed by competitive analysis of:
- [Bartender](https://www.macbartender.com/) - Menu bar organization
- [Ice](https://github.com/jordanbaird/Ice) - Open-source menu bar manager
- [SwiftBar](https://github.com/swiftbar/SwiftBar) - Plugin-based menu bar customization
- [MacMenuBar.com](https://macmenubar.com/) - Menu bar app directory
- [SaaS Landing Page](https://saaslandingpage.com/) - Landing page best practices
- [Unbounce SaaS Guide](https://unbounce.com/conversion-rate-optimization/the-state-of-saas-landing-pages/) - Conversion optimization

---

## Website Structure Suggestion

```
Home
├── Hero (headline + value prop + CTA)
├── Problem/Solution section
├── Features overview (with visuals)
│   ├── Two display modes
│   ├── Custom menu actions
│   ├── Deep links
│   └── App presets
├── Use cases (tabs or accordion)
├── Comparison tables (vs competitors)
├── Testimonials / Social proof
├── Pricing
├── FAQ
└── Download CTA
```

---

*Document created for ExtraBar website and marketing purposes. Content can be adapted for App Store listing, social media, and other marketing channels.*
