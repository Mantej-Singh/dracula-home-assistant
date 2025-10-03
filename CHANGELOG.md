# Changelog

All notable changes to this project will be documented in this file.

## [1.2.0] - 2025-10-02

### Added
- **Visual Polish & Effects** - Smooth transitions, hover effects, and loading indicators for premium feel
- **Enhanced Dropdown/Menu Styling** - Darker backgrounds (`#3b3d4a`) with prominent shadows for better depth perception
- **Media Player Enhancements** - Dedicated variables for Music Assistant (progress bars, volume, playback controls, album art)
- **History & Logbook Colors** - Multi-color graph support for tracking automation history with 5 distinct line colors
- **Map Card Support** - Comprehensive zone and person tracking colors (home, work, custom zones, person markers)
- **Dialog Enhancements** - Better popup/modal appearance with shadows and backdrop styling
- **Legacy Paper Components** - Fixed dropdown menus for older HA components

### Changed
- New `dracula-darker` color (`#3b3d4a`) for dropdown/menu depth
- New `dracula-selection` color (`#44475a`) for explicit selection highlighting
- Enhanced MDC select borders - brighter and more prominent (cyan accents)
- Dropdown icon color changed from comment gray to cyan for better visibility

### Removed
- Code editor/CodeMirror syntax highlighting variables (non-functional, removed for cleaner codebase)

### Technical
- File size increased from 350 to 502 lines (+43%)
- Added 60+ new theme variables
- Improved visual hierarchy with darker dropdown backgrounds
- Better component coverage (media players, history graphs, maps)

## [1.0.0] - 2025-10-02

### Added
- Initial release of Dracula theme for Home Assistant
- Complete Dracula color palette implementation
- Comprehensive state colors for all entity types
- Media player button visibility optimizations
- Modern 12px border radius on cards and badges
- Energy dashboard color support
- Code editor syntax highlighting with Dracula colors
- Material Design Components (MDC) full support
- Paper Components legacy support

### Features
- **12px border radius** for modern, polished appearance
- **High-contrast media controls** - Buttons clearly visible on dark cards
- **Complete state coverage** - All HA entity types have proper colors
- **Energy dashboard** - Custom colors for grid, solar, battery, gas, water
- **Code editor** - Full Dracula syntax highlighting
- **Input components** - Properly styled forms and controls

### Design Choices
- **Purple (`#bd93f9`)** as primary accent
- **Cyan (`#8be9fd`)** as secondary accent
- **Green (`#50fa7b`)** for on/active states
- **Comment gray (`#6272a4`)** for off/inactive states
- **Foreground white (`#f8f8f2`)** for high contrast on dark backgrounds

### Technical
- Based on official HA frontend theme API
- 349 lines of carefully mapped theme variables
- Follows Dracula official color specification
- Compatible with latest Home Assistant versions
