# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.26] - 2020-06-16

### Fixed
- `PhpClass` setExtends if getExtends is null in `PhpBuilder`.

## [0.2.25] - 2020-01-10

### Added
- `PhpBuilder` flag `buildAdditionalPropertyMethodsOnTrue` to create accessors for untyped additional properties.

## [0.2.24] - 2020-01-07

### Added
- Option to declare default property values in PHP classes generated from JSON schema, [#29](https://github.com/swaggest/php-code-builder/pull/29).

## [0.2.23] - 2019-12-11

### Added
- Support to use traits in `PhpClass`.

## [0.2.22] - 2019-12-02

### Fixed
- Pattern property setter regexp check.

## [0.2.21] - 2019-10-25

### Changed
- Magical `phpdoc` for nullable properties instead of explicit properties.
- Better property names collision resolution.

## [0.2.20] - 2019-10-02

### Fixed
- Missing return and argument phpdoc types for `array` and `mixed`.

## [0.2.19] - 2019-10-02

### Added
- Schema exporter split into protected methods to allow extension.

## [0.2.18] - 2019-09-22

### Fixed
- Description trimming bug.

[0.2.26]: https://github.com/swaggest/php-code-builder/compare/v0.2.25...v0.2.26
[0.2.25]: https://github.com/swaggest/php-code-builder/compare/v0.2.24...v0.2.25
[0.2.24]: https://github.com/swaggest/php-code-builder/compare/v0.2.23...v0.2.24
[0.2.23]: https://github.com/swaggest/php-code-builder/compare/v0.2.22...v0.2.23
[0.2.22]: https://github.com/swaggest/php-code-builder/compare/v0.2.21...v0.2.22
[0.2.21]: https://github.com/swaggest/php-code-builder/compare/v0.2.20...v0.2.21
[0.2.20]: https://github.com/swaggest/php-code-builder/compare/v0.2.19...v0.2.20
[0.2.19]: https://github.com/swaggest/php-code-builder/compare/v0.2.18...v0.2.19
[0.2.18]: https://github.com/swaggest/php-code-builder/compare/v0.2.17...v0.2.18
