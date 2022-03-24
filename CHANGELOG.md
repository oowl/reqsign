# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/)
and this project adheres to [Semantic Versioning](https://semver.org/).

## [v0.0.2] - 2022-03-23

### Added

- feat: Add support for azure storage (#29)
- services/azure/storage: Implement integration tests (#33)
- tests: Implement integration tests for aws v4 (#37)

### Changed

- refactor: Make time much easier to use and add unit tests (#34)
- chore(deps): Update aws-sigv4 requirement from 0.8 to 0.9 (#36)

### Fixed

- deps: reqsign needs time >= 0.3.6 to build (#27)

## v0.0.1 - 2022-03-17

Hello, reqsign!

### Added

- AWS Sigv4 Support

[v0.0.2]: https://github.com/Xuanwo/reqsign/compare/v0.0.1...v0.0.2