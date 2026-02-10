# Changelog

All notable changes to Nexus TV will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.0.5] - 2026-02-10

### Added
- Comprehensive in-app help documentation (1000+ lines)
- EPG assignment per playlist feature
- Auto EPG updates every 12 hours
- Pluto TV browser support (works without Electron)
- Enhanced error handling and logging
- Detailed troubleshooting sections in help

### Fixed
- **Channel loading issues** - All channels now display correctly
- **Hidden channels page** - Channel hiding/unhiding works perfectly
- Channel list not populating after playlist upload
- Hidden channels not being filtered properly
- EPG data not persisting correctly

### Changed
- Updated all version references to 1.0.5
- Improved help modal structure and navigation
- Enhanced playlist editor documentation
- Better EPG settings explanations

### Documentation
- Complete overhaul of in-app help system
- Added step-by-step guides for all features
- Expanded troubleshooting section
- Updated README.md with comprehensive feature list
- Updated INSTALLATION-GUIDE.md with more solutions

---

## [1.0.3] - 2026-02-08

### Added
- Right-click context menu support throughout the app
- Context menu debugging and troubleshooting tools

### Fixed
- Context menus not working in text fields
- Copy/paste functionality issues
- Text selection problems

### Changed
- Enhanced UI stability
- Improved overall performance

---

## [1.0.2] - 2026-02-07

### Added
- GitHub integration for update checker
- Better error handling and logging
- Enhanced stability improvements

### Fixed
- Persistent error messages issue
- Undefined function errors
- TV Guide reminder button state not resetting properly

### Changed
- Improved update notification system
- Better error reporting in console

---

## [1.0.1] - 2026-02-05

### Added
- Initial public release
- Core IPTV streaming functionality
- M3U playlist support (file upload and URL)
- Basic EPG/TV Guide integration
- Channel favorites system
- Search and filter functionality
- Fullscreen mode
- Multi-audio track support
- Category-based organization
- System tray integration (desktop app)
- Auto-update system
- Basic playlist editor

### Features
- Multiple playlist management
- HD/4K video playback
- Program reminders
- Channel hiding
- Watch history
- Dark theme UI
- Keyboard shortcuts

---

## [Unreleased]

### Planned Features
- [ ] Code signing certificate
- [ ] Additional theme options (light mode)
- [ ] Cloud sync for settings
- [ ] Mobile companion app
- [ ] Chromecast/AirPlay support
- [ ] Recording functionality
- [ ] Subtitle support
- [ ] Advanced parental controls
- [ ] Multi-language interface
- [ ] Custom skin support

### Under Consideration
- [ ] Import/export full app configuration
- [ ] Backup and restore functionality
- [ ] Advanced search with filters
- [ ] Channel recommendations
- [ ] Integration with additional free streaming services
- [ ] Picture-in-picture enhancements
- [ ] Gesture controls
- [ ] Voice commands

---

## Version History Summary

| Version | Release Date | Highlights |
|---------|--------------|------------|
| 1.0.5 | 2026-02-10 | Channel fixes, EPG per playlist, Auto updates, Comprehensive help |
| 1.0.3 | 2026-02-08 | Context menu fixes, Stability improvements |
| 1.0.2 | 2026-02-07 | Update system, Error handling, Bug fixes |
| 1.0.1 | 2026-02-05 | Initial release, Core features |

---

## Breaking Changes

### None yet
All updates have been backwards compatible. Settings and playlists from v1.0.1 work perfectly in v1.0.5.

---

## Migration Guide

### From v1.0.1/1.0.2/1.0.3 to v1.0.5

**No migration needed!** Simply:
1. Download the v1.0.5 installer
2. Run the installer (it updates in place)
3. Your playlists, settings, and favorites are automatically preserved

**What's preserved:**
- All playlists (M3U files and URLs)
- Favorite channels
- Hidden channels
- EPG settings
- Watch history
- User preferences
- Window size/position

**What's new after update:**
- Access new help system (Help menu)
- Assign EPG per playlist (EPG Settings)
- Enable auto EPG updates (enabled by default)
- Use Pluto TV in browser (works automatically)

---

## Known Issues

### Current (v1.0.5)
- Web version doesn't support system tray (desktop app feature only)
- Some IPTV streams may require specific codecs not included
- EPG matching depends on channel name accuracy
- Very large playlists (5000+ channels) may load slowly

### Fixed in v1.0.5
- ✅ Channels not loading after playlist upload
- ✅ Hidden channels page not working
- ✅ Pluto TV requiring Electron in browser
- ✅ EPG not assignable per playlist
- ✅ Manual EPG updates only

### Fixed in v1.0.3
- ✅ Context menus not working
- ✅ Copy/paste issues

### Fixed in v1.0.2
- ✅ Persistent error messages
- ✅ Update checker issues
- ✅ Reminder button state

---

## Support & Feedback

- **Bug Reports:** [GitHub Issues](https://github.com/ctsw05/nexus-tv-updates/issues)
- **Feature Requests:** [GitHub Issues](https://github.com/ctsw05/nexus-tv-updates/issues)
- **Discussions:** [GitHub Discussions](https://github.com/ctsw05/nexus-tv-updates/discussions)
- **Source Code:** [GitHub Repository](https://github.com/ctsw05/nexus-tv-updates)

---

## Contributors

Special thanks to everyone who has contributed to Nexus TV:
- Bug reporters who helped identify issues
- Feature requesters who suggested improvements
- Users who provided feedback and testing

---

**[1.0.5]:** https://github.com/ctsw05/nexus-tv-updates/releases/tag/v1.0.5  
**[1.0.3]:** https://github.com/ctsw05/nexus-tv-updates/releases/tag/v1.0.3  
**[1.0.2]:** https://github.com/ctsw05/nexus-tv-updates/releases/tag/v1.0.2  
**[1.0.1]:** https://github.com/ctsw05/nexus-tv-updates/releases/tag/v1.0.1  
**[Unreleased]:** https://github.com/ctsw05/nexus-tv-updates/compare/v1.0.5...HEAD
