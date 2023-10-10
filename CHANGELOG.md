# Change Log

All notable changes to the "turnip-text" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

## [0.0.1] - 2023-05-30

### Added

- Basic highlighting for comments (doesn't support raw scope syntax)
- Embedded python highlighting

## [0.0.2] - 2023-05-30

- Fix bug where hashes in raw scope open/close would be highlighted as comments
- Fix bug where escaped hashes would be highlighted as comments
- Fix bug where Python highlighting would trigger inside escaped square brackets

## [0.0.3] - 2023-07-03

- Add rule for raw text highlighting

## [0.0.4] - 2023-10-10

- Make raw text be highlighted as raw text