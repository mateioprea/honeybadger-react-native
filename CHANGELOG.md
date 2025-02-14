# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.0.7] - 2021-06-17
### Fixed
- Allow the default JS error handler to process the error after we're done with it so that RN shows the useful red info box in dev.

## [0.0.6] - 2021-06-17
### Added
- Added ability to differentiate and configure console output by log level, eliminating frivolous logging.

## [0.0.5] - 2021-06-15
### Fixed
- Removed regex named capture groups in favor of numeric capture groups in order to be able to support the Hermes JS engine.

## [0.0.4] - 2021-03-24
### Added
- honeybadger-generate-sourcemaps now generates main.jsbundle files for both iOS and Android.

## [0.0.3] - 2021-02-24
### Changed
- Changed the package of the native module for Android to io.honeybadger

## [0.0.2] - 2021-02-23
### Changed
- Rename the stackAddress key to stack_address to be more consistent with the HB spec.

### Added
- Allow for changing of the HB API key.

## [0.0.1] - 2021-02-15
### Added
- Initial release
