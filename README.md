# BlobCats
A rich repositery of BlobCat emojis, derived from Google's blob emojis

Honestly I just made this because even though these emojis were everywhere, they weren't properly licensed or credited to the artist

<picture>
 <source media="(prefers-color-scheme: dark)" srcset="https://github.com/DuckOfDisorder/BlobCats/raw/main/Banner.gif">
 <source media="(prefers-color-scheme: light)" srcset="https://github.com/DuckOfDisorder/BlobCats/raw/main/Banner.gif">
 <img alt="BlobCats Banner" src="https://github.com/DuckOfDisorder/BlobCats/raw/main/Banner.gif">
</picture>

## Installation
### Pleroma

run the following command for blobcats

```
mix pleroma.emoji get-packs blobcats -m https://raw.githubusercontent.com/DuckOfDisorder/BlobCats/main/manifest.json
```
or, for the flipped version,
```
mix pleroma.emoji get-packs blobcats_flipped -m https://raw.githubusercontent.com/DuckOfDisorder/BlobCats/main/manifest.json
```

Basically the entirety of this is stolen from [Volpeon](https://volpeon.ink/).

I would say I'm grateful but that would imply I knew what I was doing.

### Mastodon
Extract the archive and use the [Mastodon Emoji Importer](https://github.com/impiaaa/mastodon_import_emoji)

## Contribution
All emojis are taken from [Slackmojis](https://slackmojis.com/), [Blobs.gg](https://blobs.gg/) and its subsidiary servers

A special thanks goes to [Siara-San](https://www.instagram.com/sairaa.jpg/) for creating some of these

All SVG files were done by me by hand (TwT)

The banner usees the Nova Round font by Wojciech Kalinowski

## License
This repository, including the banner, is filed under Apache License 2.0

Due to the lack of explicit statement, the blob cats also fall under Apache 2.0, similar to this repository.
