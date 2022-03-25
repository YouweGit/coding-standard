# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 3.3.0 - 2021-03-25
### Added
- Copyrights
- Declare strict types
- Updated squizlabs/php_codesniffer to resolve phpunit error.

### Changed
- Vendor to Youwe
- Changed MediaCT rule names to Global.

## 3.1.0 - 2021-03-10
### Removed
- PHP 5.x support.
- Phpunit is required by mediact testing suite and is not a requirement for this module.

### Fixed
- PhpStorm 2020 has changed there config folder to a different path.

### Changed
- Refactored code to fix testing suite issues.

### Added
- [Dev Docker](https://github.com/mediact/docker-compose-development-manager)
- Compatibility with latest testing suite module.