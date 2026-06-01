This is a [yt-dlp](https://github.com/yt-dlp/yt-dlp "yt-dlp repooository") extractor plugin for [animepahe](https://animepahe.pw/ "animepahe"). It supports downloading single episodes, full playlists, and searching for content directly.

## Installation
```bash
python -m pip install -U https://github.com/yt-dlp-plugins/yt-dlp-animepahe/archive/main.zip
```
## AUR
> Use the AUR helper you have, for example paru, yay, or whatever.
```bash
yay -S yt-dlp-animepahe
```
## Usage

**1. Using url**:
```bash
# Default: all available languages
yt-dlp 'https://animepahe.pw/play/1c443926-8b78-358d-6cef-c9daf1fa3c8c/5df890ee9349d3254440096fa4a45bb754dfcb64868391d66740096a505afb33'

# Take only one language
yt-dlp --extractor-args 'animepahe:lang=ja' 'https://animepahe.pw/play/1c443926-8b78-358d-6cef-c9daf1fa3c8c/5df890ee9349d3254440096fa4a45bb754dfcb64868391d66740096a505afb33'

# Multiple languages, separate by commas
yt-dlp --extractor-args 'animepahe:lang=ja,en' 'https://animepahe.pw/play/1c443926-8b78-358d-6cef-c9daf1fa3c8c/5df890ee9349d3254440096fa4a45bb754dfcb64868391d66740096a505afb33'
```
> ⚠️ If the extractor displays `No video formats found!`, it means the language you selected is not available.

**2. Using search**:
```bash
yt-dlp 'animepahe:title'
```
---

# **Questions that might be asked**
**Q:** Why doesn't it revert to available languages if the language I selected isn't available?

**A:** If you're using a filter but it's not available, what's the difference between using the filter and not using it? Please fix it yourself if you need the feature.

## Support the Project ☕
**If this extractor helps you save time, consider supporting its maintenance**:

<div align="left">

[![Trakteer](https://img.shields.io/badge/Trakteer-F16061?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white)](https://trakteer.id/asep5k) [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/rezaoctavian496) [![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/aspe) 

</div>

