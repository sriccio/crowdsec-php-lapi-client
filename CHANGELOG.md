# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## Public API

The purpose of this section is to declare the public API of this library as required by  [item 1 of semantic versioning specification](https://semver.org/spec/v2.0.0.html#spec-item-1).

The public API of this library consists of all public or protected methods, properties and constants belonging to
the following files:
- `src/Bouncer.php`
- `src/ClientException.php`
- `src/Configuration.php`
- `src/Constants.php`

---


## [1.0.1](https://github.com/crowdsecurity/php-lapi-client/releases/tag/v1.0.1) - 2023-01-27
[_Compare with previous release_](https://github.com/crowdsecurity/php-lapi-client/compare/v1.0.0...v1.0.1)

### Added

- Add public API declaration

---


## [1.0.0](https://github.com/crowdsecurity/php-lapi-client/releases/tag/v1.0.0) - 2023-01-27
[_Compare with previous release_](https://github.com/crowdsecurity/php-lapi-client/compare/v0.4.0...v1.0.0)

### Changed

- Change version to `1.0.0`: first stable release

---


## [0.4.0](https://github.com/crowdsecurity/php-lapi-client/releases/tag/v0.4.0) - 2023-01-12
[_Compare with previous release_](https://github.com/crowdsecurity/php-lapi-client/compare/v0.3.0...v0.4.0)

### Changed

- Unexpected configuration keys are automatically removed by a new `cleanConfigs` method
- Update some logs

---


## [0.3.0](https://github.com/crowdsecurity/php-lapi-client/releases/tag/v0.3.0) - 2023-01-05
[_Compare with previous release_](https://github.com/crowdsecurity/php-lapi-client/compare/v0.2.0...v0.3.0)

### Changed

- Do not throw error on LAPI 404 response
- Use compressed requests for `Curl`
- Use message log instead of a context message field

---


## [0.2.0](https://github.com/crowdsecurity/php-lapi-client/releases/tag/v0.2.0) - 2022-12-29
[_Compare with previous release_](https://github.com/crowdsecurity/php-lapi-client/compare/v0.1.0...v0.2.0)

### Changed

- Lowercase all scope constants (`ip`, `range`, `country`)

---

## [0.1.0](https://github.com/crowdsecurity/php-lapi-client/releases/tag/v0.1.0) - 2022-12-23
[_Compare with previous release_](https://github.com/crowdsecurity/php-lapi-client/compare/v0.0.1...v0.1.0)

### Changed

- Increase default timeout to 120 seconds and allow unlimited timeout for negative `api_timeout` setting value

### Added
- Add `user_agent_version` configuration

---


## [0.0.1](https://github.com/crowdsecurity/php-lapi-client/releases/tag/v0.0.1) - 2022-12-08
### Added
- Initial release
