# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.0.3]

### Added

- Ignore lifecycle changes in `initial_group_config`

### Changed

- Remove `INITIAL_GROUP_CONFIG_UNSPECIFIED` as an option from `initial_group_config` since
  Google recommends to not use it as written in
  https://cloud.google.com/identity/docs/reference/rest/v1beta1/groups/create#initialgroupconfig

## [0.0.2]

### Added

- Support for provider 4.x

## [0.0.1]

### Added

- Initial Implementation

[unreleased]: https://github.com/mineiros-io/terraform-google-identity-group/compare/v0.0.3...HEAD
[0.0.3]: https://github.com/mineiros-io/terraform-google-identity-group/compare/v0.0.2...v0.0.3
[0.0.2]: https://github.com/mineiros-io/terraform-google-identity-group/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/mineiros-io/terraform-google-identity-group/releases/tag/v0.0.1
