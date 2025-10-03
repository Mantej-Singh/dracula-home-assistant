# Dracula for [Home Assistant](https://www.home-assistant.io/)

> A dark theme for [Home Assistant](https://www.home-assistant.io/).

![Dashboard Screenshot](./docs/supporting%20imgs/screenshot-dashboard.png)

### Code Editor View
![Code Editor Screenshot](./docs/supporting%20imgs/screenshot-code-editor.png)

## Install

### Via HACS (Recommended)

1. Open **HACS** in Home Assistant
2. Go to **Frontend**
3. Click the **⋮** menu (top right) → **Custom repositories**
4. Add this repository:
   - **URL**: `https://github.com/dracula/home-assistant`
   - **Category**: `Theme`
5. Click **Download** on the Dracula theme
6. **Restart Home Assistant**
7. Go to your **Profile** → Select **Dracula** theme

### Manual Installation

1. Copy `themes/dracula.yaml` to `<config>/themes/dracula.yaml`
2. Add to your `configuration.yaml`:

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

3. Restart Home Assistant
4. Go to your **Profile** → Select **Dracula** theme

## Features

- ✨ Authentic [Dracula color palette](https://draculatheme.com/contribute)
- 🎨 Complete theme coverage (cards, sidebar, dialogs, inputs, dropdowns)
- 🎮 Enhanced media player controls (Music Assistant support, progress bars, album art)
- 🔄 Comprehensive state colors for all entity types
- 📊 Energy dashboard support
- 📈 Multi-color history graphs and logbook styling
- 🗺️ Map card support with custom zone colors
- 🎯 Modern 12px border radius on cards
- ✨ Smooth transitions and hover effects for premium feel
- 🌙 Dark mode optimized with enhanced depth perception

## Color Palette

| Color      | Hex       | Usage                          |
|------------|-----------|--------------------------------|
| Background | `#282a36` | Main background                |
| Current    | `#44475a` | Cards, elevated surfaces       |
| Foreground | `#f8f8f2` | Primary text                   |
| Comment    | `#6272a4` | Secondary text, inactive states|
| Cyan       | `#8be9fd` | Accents, info, links           |
| Green      | `#50fa7b` | Success, on states             |
| Orange     | `#ffb86c` | Warnings                       |
| Pink       | `#ff79c6` | Highlights                     |
| Purple     | `#bd93f9` | Primary accent                 |
| Red        | `#ff5555` | Errors, critical states        |
| Yellow     | `#f1fa8c` | Attention, lights on           |

## Acknowledgments

This theme was created following official [Home Assistant theme guidelines](https://www.home-assistant.io/integrations/frontend/) and inspired by the excellent work of the Home Assistant theme community.

## Team

This theme is maintained by:

| [![Mantej Singh](https://avatars.githubusercontent.com/u/19365795?s=100&v=4)](https://github.com/Mantej-Singh) |
| --- |
| [Mantej Singh](https://github.com/Mantej-Singh) |

## Community

- [Twitter](https://twitter.com/draculatheme) - Updates about Dracula themes
- [GitHub Discussions](https://github.com/dracula/dracula-theme/discussions) - Questions and discussions
- [Discord](https://draculatheme.com/discord-invite) - Chat with the community
- [Home Assistant Community](https://community.home-assistant.io/) - HA-specific help

## Contributing

Found a bug or want to improve the theme? Check out [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

## License

[MIT License](./LICENSE)
