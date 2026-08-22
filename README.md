# FS_Forums_Archive

Unofficial archive of the [Fatshark Games forums](https://forums.fatsharkgames.com/), created for historical preservation purposes. 
All content, trademarks, and copyrights remain the property of [Fatshark AB](https://www.fatshark.se/) and their respective authors.

## Links

* Live Archive: https://vladm0z.github.io/FS_Forums_Archive/
* Build Notebook: https://github.com/Vladm0z/FS_Forums_Archive/blob/main/FS_Forums_Archive.ipynb

## Overview

This repository contains a static HTML mirror of the official Fatshark forums (forums.fatsharkgames.com). The archive is generated and maintained using a Google Colab Python pipeline that interacts directly with the Discourse JSON API. 

The generated site includes:
* Category and subcategory navigation mirroring the original forum structure
* Localized user profiles compiled from post history
* Paginated thread listings with dark/light theme

## Usage

The `FS_Forums_Archive.ipynb` notebook provides the complete pipeline for both the full scrape and all subsequent updates. The pipeline relies on Google Drive for JSON storage and requires a GitHub Personal Access Token to publish the rendered HTML to the `gh-pages` branch.

## Disclaimer

This is an unofficial archival project. It is not affiliated with, endorsed by, or connected to Fatshark Games.
