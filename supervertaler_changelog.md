# Changelog

All notable changes to Supervertaler will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- New features to be added

### Changed
- Changes in existing functionality

### Fixed
- Bug fixes

## [2.1.0] - 2025-09-04

### Added
- Multi-AI provider support (Claude, Gemini, OpenAI)
- Image context integration for visual references in translations
- Custom instructions text field for on-the-fly system prompt modifications
- Translation Memory support (.txt/.tmx files)
- Tracked-changes import from memoQ-generated bilingual DOCX files
- Chunking system for large documents
- Full document context consideration for better accuracy

### Changed
- Enhanced GUI with image folder selection
- Improved contextual understanding with multiple context sources
- Updated system prompt structure for better AI performance

### Fixed
- Pillow library dependency handling
- Figure reference normalization improvements

## [2.0.0] - 2025-08-31

### Added
- PROOFREAD mode alongside existing TRANSLATE mode
- Multimodal prompt support for image-aware translations
- Drawings Image Folder functionality
- Support for multiple image formats (.png, .jpg, .jpeg, .webp)
- Figure reference detection and normalization

### Changed
- Major refactor of the translation engine
- Improved chunk processing for multimodal content
- Enhanced error handling and logging

### Breaking Changes
- API structure changes for multi-provider support
- Configuration file format updates

## [1.5.0] - 2025-07-02

### Added
- Enhanced GUI interface
- Better error reporting and logging
- Improved file handling capabilities

### Changed
- Optimized performance for larger documents
- Updated AI model compatibility

### Fixed
- Various stability improvements
- Memory usage optimizations

## [1.0.0] - 2025-05-20

### Added
- Initial release of Supervertaler
- Basic AI-powered translation functionality
- Support for text file input/output
- Core GUI interface
- Basic chunking system

### Features
- Single AI provider support
- Text-only translation capabilities
- Basic Translation Memory integration
