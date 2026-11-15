# WAVEFORGE

> Browser-native sound editor & recorder. A Sound Forge-style workflow in a single HTML file.  
> Drop a file → edit → render. Zero dependencies.

[🌐 Live Demo](https://effdst.github.io/WaveForge/) | [⬇ Portable Build (Releases)](https://github.com/effdst/WaveForge/releases)

---

## 📡 About

WAVEFORGE is a desktop-grade audio editor that runs entirely in the browser on the Web Audio API. 
No installation, no accounts, no frameworks. Waveform editing, real-time analyzers, an FX chain, 
markers, and offline rendering — in one self-contained file. Works offline from a USB drive.

## ✂️ Features

- **Editing**: cut · copy · paste · trim · silence · fade in/out · gain · reverse · invert · time stretch · denoise
- **Analyzers**: level (dBFS) · spectrum · vector · peak / RMS meters
- **FX Chain**: bus compressor (SSL-style) · de-esser · parametric EQ (bell / shelves / HP / LP / notch / band) · limiter + normalize
- **Markers**: rename · snap · follow · zoom / fit-to-window
- **Audio I/O**: input / output device selection, sample rate control
- **Import**: WAV · MP3 · OGG · FLAC · M4A (drag & drop or open dialog)
- **Export**: WAV (16 / 24 / 32-float) · MP3 (128–320 kbps) · original / 44.1 / 48 kHz
- **System**: undo / redo · offline processing with progress · bilingual UI (EN / RU)

## ⚙️ System Requirements

- **Engine**: Web Audio API
- **Dependencies**: 0 (Zero)
- **Installation**: None (Single File)
- **Offline Mode**: Yes (runs from local disk or USB drive)
- **Browsers**: Chrome / Edge recommended (widest codec support) · Safari · Firefox

## 🖥 Portable Version

The portable build runs offline without a browser tab — launch it from a folder or USB drive. 
Downloads are published in [Releases](https://github.com/effdst/WaveForge/releases).

## 📂 Repository Structure

```text
.
├── index.html          # Redirect to the editor
├── waveforge.html      # The editor (single file, EN/RU)
└── README.md