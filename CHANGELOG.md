# Changelog

All notable changes to the **GEMMA** (GIS Extension for Map Management and Analysis) QGIS plugin will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.1.0-RC1] - 2026

### Highlights
- Improved QGIS repository UI with enhanced hero section layout and dynamic download links
- Added automated release workflows and plugin metadata support for beta channels
- Renamed plugin tag from 'GEMMA' to 'gemma-plugin' for consistency
- Implemented automated CI/CD pipeline for beta plugin releases and repository metadata updates
- Created VitePress documentation site with automated deployment and release management workflows
- Added changelog file for GEMMA plugin version history and updates
- Integrated QGIS repository card with clipboard copy functionality and documentation guide
- Updated release workflow badge and refactored README layout for better clarity

## [3.0.0] - 2026

### Added
- **VitePress Documentation Site**: Published interactive documentation hosted via GitHub Pages with full user guide, tool documentation, and getting started instructions.
- **Geometry Repair Toolkit**: Integrated automated geometry validation and repair tool (detect duplicate geometries, null geometries, invalid shapes, wrong feature types with auto-fix).
- **CI/CD Workflows**: Added GitHub Actions workflows for automated plugin packaging & release (`release-plugin.yml`) and documentation site deployment (`deploy-docs.yml`).

### Changed
- Improved overall performance and stability of processing algorithms and UI widgets.
- Renamed release workflow from QGIS Plugin to GEMMA Plugin.
- Harmonized branding and nomenclature to GEMMA across all UI elements and documentation.

## [2.0.0]

### Added
- **Create Enumeration Areas**: Added EA delineation capabilities for census and survey field operations.
- **Package for QField Enhancements**: Improved package dialog with drag-and-drop layer management for QField exports.
- **Interactive EA Preview Widget**: Interactive map preview for candidate enumeration area polygons.
- **GitHub Templates**: Added issue templates for bug reports and feature requests.

### Changed
- Registered EA Delineation processing provider with new UI actions.
- Introduced default presets for enhanced user experience.
- Removed unnecessary cache files to streamline plugin performance.
- Updated repository URLs and documentation links.

## [1.2.0]

### Added
- **Fill Polygon Gaps**: Automatically fill gaps between polygon boundaries.
- **Update Metadata**: Auto-populate LGU PSGC metadata using reference lookup tables.
- **Fix LGU CRS / Geometry**: Reposition and rescale LGU boundary layers to standard EPSG:4326.

## [1.1.0]

### Added
- Integrated **Package for QField** tool from `qfieldmod` plugin.

## [1.0.0]

### Added
- Initial release featuring the **MBI Checker** (Gaps and Overlaps Checker).
