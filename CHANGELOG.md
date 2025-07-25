# Changelog Application Profiles

NOTE:

## Table of contents

- **[r1.1](#r11)**

**Please be aware that the project will have frequent updates to the main branch. There are no compatibility guarantees associated with code in any branch, including main, until it has been released. For example, changes may be reverted before a release is published. For the best results, use the latest published release.**

The below sections record the changes for each API version in each release as follows:

* for an alpha release, the delta with respect to the previous release
* for the first release-candidate, all changes since the last public release
* for subsequent release-candidate(s), only the delta to the previous release-candidate
* for a public release, the consolidated changes since the previous public release
Note: this API had former releases in the [ConnectivityInsights](https://github.com/camaraproject/ConnectivityInsights/releases) repository.
# r1.1
## Release Notes

This release contains the definition and documentation of
* application-profiles v0.5.0-rc.1

The API definition(s) are based on
* Commonalities v0.6.0-rc.1 (r3.2)
* Identity and Consent Management v0.4.0-rc.1 (r3.2)

*  **r1.1 release of ApplicationProfiles has the following API definitions:**

    *  **application-profiles v0.5.0-rc.1**
    [[View it on ReDoc]](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/camaraproject/ApplicationProfiles/r1.1/code/API_definitions/application-profiles.yaml&nocors)
    [[View it on Swagger Editor]](https://camaraproject.github.io/swagger-ui/?url=https://raw.githubusercontent.com/camaraproject/ApplicationProfiles/r1.1/code/API_definitions/application-profiles.yaml)
    [[OpenAPI]](https://raw.githubusercontent.com/camaraproject/ApplicationProfiles/r1.1/code/API_definitions/application-profiles.yaml)


### Added

* New `DeviceResponse` object in responses limited to one identifier.
* Clarifications on non-documented error responses.
* Support for compute resource requirements related to the application.

### Changed

* Updated string pattern for `x-correlator`headers.

### Removed

* `verificationResult: UNKNOWN` for 200 responses.
* Error `422 IDENTIFIER_MISMATCH`.
* Error `401 AUTHENTICATION_REQUIRED`.

**Full Changelog**: https://github.com/camaraproject/ApplicationProfiles/commits/r1.1
