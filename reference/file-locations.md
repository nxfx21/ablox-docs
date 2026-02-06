# File Locations

Complete reference of AppleBlox file locations.

## Application Files

| Path | Description |
|------|-------------|
| `/Applications/AppleBlox.app` | Main application bundle |
| `/Applications/Roblox.app` | Roblox installation |

## Data Directory

All AppleBlox data lives in:

```
~/Library/Application Support/AppleBlox/
```

### Subdirectories

| Path | Contents |
|------|----------|
| `mods/` | Your installed mods |
| `cache/` | Mod backups, font cache, game cache |
| `cache/mods/Resources/` | Backup of original Roblox files |
| `cache/fonts/` | Custom font storage |
| `logs/` | Application log files |
| `config/` | Settings JSON files |
| `icons/` | Custom app icons |
| `theme.css` | Custom CSS theme file |

## Roblox Files

| Path | Description |
|------|-------------|
| `/Applications/Roblox.app/Contents/Resources/` | Where mods are applied |
| `~/Library/Preferences/com.roblox.Roblox/ClientAppSettings.json` | FastFlags configuration |
| `/Applications/Roblox.app/Contents/MacOS/RobloxPlayer` | Roblox executable |

## Quick Access Commands

```bash
# Open data directory
open ~/Library/Application\ Support/AppleBlox/

# Open mods folder
open ~/Library/Application\ Support/AppleBlox/mods/

# View logs
open ~/Library/Application\ Support/AppleBlox/logs/
```
