# global-music-feed — PUBLIC ChatGPT feed

Public machine-readable output generated automatically by the private `global-music-rss` collector.

This repository contains **only the compact feed files needed by ChatGPT**. It does not contain the canonical 262-source CSV/OPML registry, source feed URLs, private state, health diagnostics, or daily archive.

After the private collector runs successfully, the usable entry point is:

`https://raw.githubusercontent.com/<YOUR-GITHUB-USERNAME>/global-music-feed/main/api/manifest.json`

The `api/` directory is updated automatically. Do not edit generated JSON files by hand.
