# Changelog

All notable changes to this project are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and the project uses [Semantic Versioning](https://semver.org/).

## [Unreleased]

## [1.0.0] - 2026-09-24

First public release: a native macOS rebuild of the BMW Accessories Configurator 10.0.

### Added
- Native Swift/SwiftUI app for macOS 26 and later (Apple Silicon and Intel).
- Reimplemented COSY/iris renderer: `.map`/`.z`/`.col` decoding, vehicle rule scripts, depth-sorted layer compositing, blend modes, paint colouring and legacy wheel mounting.
- All 10 series and 37 body styles with every engine from the original data.
- Paint, wheels (with tyre fitments), exterior, interior, communication and luggage accessories, following the original option rules.
- Front, side, rear, dashboard and 360° interior panorama views, with zoom and pan.
- Undo and redo; save and open configurations (`.bmwconfig`).
- Image export (PNG/JPEG) and a printable A4 summary sheet.
- Eight languages from the original translation table.
- Liquid Glass app icon (Icon Composer).
- **Help → Report a Bug…** and **Copy Diagnostic Info**.
- First-run **Import Data…**: copies the configurator data (from the archive.org ISO) into `~/Library/Application Support/BMW Configurator`, so the download can be deleted.

[Unreleased]: ../../compare/v1.0.0...HEAD
[1.0.0]: ../../releases/tag/v1.0.0
