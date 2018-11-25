# Role: regional

This role installs and configures locales.
Compatibility tested with:
 * Debian 8
 * Debian 9
 * Fedora 25 Server

## Configuration
| Name | Default | Description |
|------|---------|-------------|
| `regional_locales_installed` | `["en_US.UTF-8", "de_CH.UTF-8"]` | Locales to install |
| `regional_locale_ui` |`en_US.UTF-8` | Locale to use by default |
| `regional_locale_spec` | `de_CH.UTF-8` | Locale to use for country-specific formats |

## License
GPLv3
