# Changelog

All notable changes to the **GIFforge** suite across the Browser Extension, VS Code Extension, and Core Engine will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [1.0.0] - 2026-10-17

### 🚀 GIFforge Browser Extension
- **Zero-Server GIF Engine**: Fully ported frame selection and quantization pipeline to client-side JavaScript.
- **Custom Bounding Region**: Interactive drag-and-drop region selection directly on live video preview before recording.
- **Native Video Import**: Convert existing `.mp4`, `.webm`, and `.mov` screen recordings to optimized GIFs.
- **Automated AI Frame Ranking**: Scoring module combining pixel motion deltas, structural discontinuity bonuses, and temporal decay distribution.
- **Chrome & Edge Web Store Compliance**: Built to full Manifest V3 specifications with strict permission isolation.

### 🛠️ VS Code Extension (v1.0.10)
- Full platform support for Windows (`gdigrab`), Linux (`x11grab`), and macOS (`avfoundation`).
- Live recording elapsed timer display in extension webview panel.
- Enhanced dual-pass palette encoding with `palettegen=stats_mode=diff` and Sierra 2-4A dithering.

---

## [0.1.0] - 2026-08-17
- Initial preview prototype for in-browser recording via `getDisplayMedia`.
- Proof of concept for client-side GIF rendering using `gifenc`.
