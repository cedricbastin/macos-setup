# System Configuration

## System Preferences

**General**

- [ ] 'Close windows when quitting an app' (full screen apps will re-open in full-screen)

iCloud
Apple Pay

**Keyboard**

- Keyboard
	- [x] Show keyboard and emoji viewers in meny bar (I mostly use it to find symbols)
	- Customize Control Strip
		- Drag 'Play/Pause' instead of 'Mute'
- Input Sources
	- [x] Show Input menu in menu bar


**Accessibility**

- Display
	- Cursor
		- [ ] Shake mouse pointer to locate
- Pointer Control
	- Mouse & Trackpad
		- Double-click speed: 9/10
		- [x] Spring-loaded delay: 1/10	

## Menu Bar

- Battery
	- ✓ Show Percentage
- Input Source
	- Hide Input Source Name

## Finder

Preferences:

- General
	- New Finder Windows show: <Your favourite folder>
- Tags
	- drag your personalized (iCloud synces) tags into 'Favourite Tags'
- Sidebar
	- Hide: Recents, Movies, Music, Pictures
- Advanced:
	- [x] Show all filename extensions
	- [ ] Show warning before changing an extension
	- [ ] Show warning before removing from iCloud Drive
	- Keep folder on top

## Keyboard shortcuts 

Modifier Key names and symbols:

- Cmd ⌘ Command
- Ctrl ⌃ Control
- Alt ⌥ Option
- Shift ⇧
- Caps Lock ⇪
- Fn Function

- App Shortcuts
	- `⌘?` aka `⌘⇧/` Show Help menu

## Screenshots

- `⇧⌘3` take a screenshot of entire Desktop
- `⇧⌘4` take screenshot of selection `space` to move selection `Esc` to discard
- `⇧⌘5` Change default location where screenshots are saved to
- `defaults write com.apple.screencapture name ""` to remove the `Screen Shot` prefix in the file name (will still contain an empty space though)

## Terminal commands

Expand print dialog by default:
`defaults write -g PMPrintingExpandedStateForPrint -bool TRUE`

Add dock spaces:
`defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}'; killall Dock`

Dock transition/reveal delay:
`defaults write com.apple.dock autohide-delay -float 0; killall Dock`
