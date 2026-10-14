<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.svg">
    <img src="assets/logo-light.svg" width="120" alt="Synaris logo">
  </picture>
</p>

<h1 align="center">Synaris</h1>

<p align="center">An offline chemistry workbench for professional and PhD chemists.</p>

<p align="center">
  <a href="https://github.com/PaxterCoding/synaris-releases/releases/latest"><b>Download for Windows (x64)</b></a> · <a href="https://github.com/PaxterCoding/synaris-releases/releases/latest"><b>Download for macOS (Apple Silicon)</b></a>
</p>

<p align="center"><sub>Synaris is in early testing. If no release is listed yet, check back soon.</sub></p>

## What's inside

- **Structure editor:** fast drawing with templates, R groups and publication-ready journal styles (ACS, RSC, Nature, Angewandte and more); export to CDXML, MOL, SMILES, InChI, SVG, PDF and PNG.
- **Retrosynthesis:** proposes disconnections and routes, with forward reaction prediction that checks selectivity.
- **Spectra prediction:** 1H and 13C NMR (including DEPT) and 2D NMR, with peaks linked to atoms.
- **Reaction library:** named reactions with generic schemes, conditions and literature.
- **Built-in assistant:** ask for a reaction, a structure or a calculation in plain words; it works without any AI model. Optionally connect a local model through LM Studio.

## Private by design

Synaris runs on your computer. Your structures, spectra and notes are stored on your machine, and the core tools work without an internet connection. It goes online for the daily update check and for a few lookups such as finding a structure by name.

## System requirements

| Platform | Requirement |
|---|---|
| Windows | Windows 10 or 11, 64-bit (x64) |
| macOS | Apple Silicon (M1 or later) |

## Install

### Windows

1. Download the Synaris setup `.exe` from the [latest release](https://github.com/PaxterCoding/synaris-releases/releases/latest).
2. Run it.

Because the installer is not yet code-signed, Windows SmartScreen may show "Windows protected your PC". Click **More info**, then **Run anyway**.

### macOS

1. Download the `.dmg` from the [latest release](https://github.com/PaxterCoding/synaris-releases/releases/latest) and drag Synaris into Applications.

Because the app is not yet notarised by Apple, macOS may say it is damaged or cannot be opened. Open Terminal and run the following command, then open Synaris again.

```sh
xattr -cr /Applications/Synaris.app
```

## Updates

Synaris checks for a new version once a day. When one is available it asks before installing: choose **Restart and update**, or **Later** to keep working.

## Licence

Synaris is proprietary software. Copyright (c) 2026 PaxterCoding. All rights reserved. Third-party licences are included with the app.
