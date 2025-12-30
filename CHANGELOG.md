# PA-Leatrix_Plus Changelog

All notable changes to this project will be documented in this file.

## [3.0.131-PA1] - 2025-12-29

### Fixed
- **InterfaceOptionsControlsPanelAutoLootCorpse Error** - Added nil check before accessing `InterfaceOptionsControlsPanelAutoLootCorpse` UI element which doesn't exist in Project Ascension's modified 3.3.5 client. This was causing a Lua error on PLAYER_LOGIN and ADDON_LOADED events.

### Changed
- Added nil check wrapper around Interface Options panel auto-loot checkbox modification (lines 2218-2230 in `Leatrix_Plus.lua`)

## [3.0.131] - Original Release

### Features (from upstream Sattva-108 port)
- Faster looting with SpeedyAutoLoot integration
- Quest automation (accept/turn-in)
- Auto sell junk items
- Auto repair at vendors
- Chat enhancements and customization
- Minimap improvements
- Tooltip enhancements
- Error frame customization
- Flight path enhancements
- Social controls (block duels, invites, etc.)
- And many more quality of life features

---

*For the complete upstream changelog, see [CHANGELOG.txt](CHANGELOG.txt)*
