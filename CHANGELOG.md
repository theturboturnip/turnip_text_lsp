# Change Log

All notable changes to the "turnip-text" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

## [0.1.0] - 2024-05-20

### Added
- Autocomplete when opening raw scope for N &lt;= 3
- Update code to support new dash syntax, that only ends when dashes match
- Format eval-brackets with dashes as strings, so the dashes and the brackets have a consistent look
- Format the first word of eval-brackets without dashes to look like function calls, because that's what they usually are.
- Support for escaped newlines in comments
- En and em-dash shortcut highlighting

### Fixed

- Make raw scope formatting only end when hashes match

### Removed

- Remove extraneous "bracket" definitions

## [0.0.4] - 2023-10-10

### Changed

- Make raw text be highlighted as raw text

## [0.0.3] - 2023-07-03

### Added

- Raw text highlighting

## [0.0.2] - 2023-05-30

### Fixed

- Fix bug where hashes in raw scope open/close would be highlighted as comments
- Fix bug where escaped hashes would be highlighted as comments
- Fix bug where Python highlighting would trigger inside escaped square brackets

## [0.0.1] - 2023-05-30

### Added

- Basic highlighting for comments (doesn't support raw scope syntax)
- Embedded python highlighting