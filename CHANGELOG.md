# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed
- Refactor variable declaration and JSON output

## [1.2.0] - 2020-08-13

### Added
- Add 'Revision' to supported title_page metadata

### Changed
- Update LICENSE copyright date and holder

## [1.1.0] - 2020-08-13

### Added
- Add support for 'Contact info' to title_page RegEx and HTML rendering

### Changed
- Refactor title_page RegEx reducing duplication for 'Date' and 'Draft date'
- Refactor switch statement so that author and authors return same result
- Refactor switch statement so that draft_date and date return same result

## [1.0.2] - 2020-08-13

### Added
- Add title to package.json
- Add language highlighting to README code snippets

## [1.0.1] - 2020-08-13

### Added
- List Matt Daly as a contributor

### Changed
- Rename package to @thombruce/fountain.js

### Removed
- Delete minified file

## [1.0.0] - 2020-08-13

### Added
- Fork repo from mattdaly/Fountain.js
- Add package.json
- Add CHANGELOG.md

### Changed
- Rename readme.md > README.md
- Rename LICENSE.md > LICENSE

### Removed
- Delete /app site directory
- Delete /samples directory

[Unreleased]: https://github.com/thombruce/fountain.js/compare/v1.2.0...HEAD
[1.2.0]: https://github.com/thombruce/fountain.js/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/thombruce/fountain.js/compare/v1.0.2...v1.1.0
[1.0.2]: https://github.com/thombruce/fountain.js/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/thombruce/fountain.js/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/thombruce/fountain.js/releases/tag/v1.0.0