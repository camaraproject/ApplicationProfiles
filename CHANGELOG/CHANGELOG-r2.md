# Changelog ApplicationProfiles

<!-- TOC:START -->
## Table of Contents
- [r2.1](#r21)
<!-- TOC:END -->

**Please be aware that the project will have frequent updates to the main branch. There are no compatibility guarantees associated with code in any branch, including main, until it has been released. For example, changes may be reverted before a release is published. For the best results, use the latest published release.**

The below sections record the changes for each API version in each release as follows:

* for an alpha release, the delta with respect to the previous release
* for the first release-candidate, all changes since the last public release
* for subsequent release-candidate(s), only the delta to the previous release-candidate
* for a public release, the consolidated changes since the previous public release

# r2.1

## Release Notes

This release candidate contains the definition and documentation of
* application-profiles 0.6.0-rc.1

The API definition(s) are based on
* Commonalities r4.3 (0.8.0)
* Identity and Consent Management r4.2 (0.5.0)

## application-profiles 0.6.0-rc.1

**application-profiles 0.6.0-rc.1 is a release-candidate version of this API.**

Changes documented below are compared to version 0.5.0.

- API definition **with inline documentation**:
  - [View it on ReDoc](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/camaraproject/ApplicationProfiles/r2.1/code/API_definitions/application-profiles.yaml&nocors)
  - [View it on Swagger Editor](https://camaraproject.github.io/swagger-ui/?url=https://raw.githubusercontent.com/camaraproject/ApplicationProfiles/r2.1/code/API_definitions/application-profiles.yaml)
  - OpenAPI [YAML spec file](https://github.com/camaraproject/ApplicationProfiles/blob/r2.1/code/API_definitions/application-profiles.yaml)

### Breaking changes

* N/A

### Added

* N/A

### Changed

* N/A

### Fixed

* fix: correct DELETE response code to 204 in test feature file by @maheshc01 in https://github.com/camaraproject/ApplicationProfiles/pull/35
* fix: align API with CAMARA Commonalities r4.3 validation requirements by @maheshc01 in https://github.com/camaraproject/ApplicationProfiles/pull/33
* fix: added missing x-correlator headers to 200 / 204 responses by @Kevsy in https://github.com/camaraproject/ApplicationProfiles/pull/38

### Removed

* N/A

**Full Changelog**: https://github.com/camaraproject/ApplicationProfiles/compare/r1.2...r2.1

