# It does not work at this time due to ext.to's bot protection.

# EXT.TO Plugin for Unchained Android

This repository contains a search plugin for [EXT.TO](https://ext.to) that works with the [Unchained Android](https://github.com/LivingWithHippos/unchained-android) app.

## What is this?

This plugin allows you to search for torrents on EXT.TO directly from the Unchained Android app, which interfaces with Real-Debrid to download and stream content.

## Installation

### Method 1: Direct Installation

1. Download the `ext.to.unchained` file from this repository
2. Transfer it to your Android device
3. Open the file with your file manager
4. Select "Unchained" as the app to open it with
5. The plugin will be installed automatically
6. Restart Unchained if the plugin doesn't appear

### Method 2: Repository Installation

1. Open Unchained Android app
2. Go to Settings → Search Engines → Repositories
3. Add this repository URL: `https://raw.githubusercontent.com/jeremysimons/unchained-ext-to-plugin/main/repository.json`
4. The plugin will appear in your available plugins list
5. Install it from there

## Features

- Search across multiple categories:
  - All torrents
  - Movies
  - TV Shows
  - Music
  - Games
  - Applications
  - Anime

- Results sorted by seeders (highest first)
- Extracts: Name, Seeders, Leechers, Size, Magnet links, Torrent files

## Known Issues

⚠️ **Cloudflare Protection**: EXT.TO uses Cloudflare anti-bot protection, which may cause the plugin to fail intermittently. This is a limitation of the site, not the plugin.

Possible solutions:
- Access EXT.TO in your browser first to pass the Cloudflare check
- Use a VPN if the site is blocked in your region
- Wait and retry if searches fail

## Updating

The plugin will notify you when updates are available if you installed it via the repository method.

## Support

If you encounter issues:
1. Make sure you're using the latest version of Unchained Android
2. Check that EXT.TO is accessible in your region
3. Try accessing the site in a browser first
4. Report issues in the [Issues](https://github.com/jeremysimons/unchained-ext-to-plugin/issues) section

## Contributing

Feel free to submit pull requests to improve the plugin! Common improvements:
- Better regex patterns for data extraction
- Support for additional categories
- Workarounds for Cloudflare protection

## License

This plugin is provided as-is for use with Unchained Android. Use responsibly and in accordance with your local laws.

## Credits

- Plugin format based on [Unchained Plugins Documentation](https://github.com/LivingWithHippos/unchained-android/wiki/Search-Engine)
- Created for use with [Unchained Android](https://github.com/LivingWithHippos/unchained-android)

## Disclaimer

This plugin is for educational purposes. The author is not responsible for how it is used. Always respect copyright laws and use legal sources for content.
