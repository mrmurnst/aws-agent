# Change Log
All notable changes to this project will be documented in this file. This change log follows the conventions of [keepachangelog.com](http://keepachangelog.com/).

## [Unreleased]

## [0.1.0]
### Added
- this CHANGELOG.
- switched to being a standard WebExtension and shimming to support Chrome.

### Changed
- switched to async interfaces where possible.
- we build dialog.js with browserify now too.
- cleaned up the UI a little.

### Fixed
- connection filter wasn't catching pre-signed S3 URLs.

## [0.0.9]
### Changed
- started using jsbeautify.
- switched from uglify to babili.
- added production flag to gulp.

### Fixed
- request payloads being truncated to 4096 bytes.

## [0.0.8]
### Changed
- S3 URL regex wasn't doing what I thought it was.

## [0.0.7]
### Added
- LICENSE
- step in filter to skip S3 URLs.

### Fixed
- handling of encoded characters in URLs.

## [0.0.6]
### Added
- filter at `onRequest` so we skip connections we don't care about sooner.
- step in filter to skip S3 URLs.

## [0.0.5]
### Changed
- use npm's version hooks.

## [0.0.4]
### Changed
- build script stuff to make the version in manifest.json track the one in package.json.

## [0.0.3]
### Changed
- version bump for no apparent reason.

## [0.0.2]
### Changed
- version bump for no apparent reason.

[Unreleased]: https://github.com/Liath/aws-agent/bulk-importer/compare/0.0.9...HEAD
[0.0.9]: https://github.com/Liath/aws-agent/commit/5d051100aa288071b5ef68a7f098d59764051831
[0.0.8]: https://github.com/Liath/aws-agent/commit/255c3d7bb42fb3422516346f2de6a1a21f037324
[0.0.7]: https://github.com/Liath/aws-agent/commit/4f0150e176d944765700afef9d47d8241306d853
[0.0.6]: https://github.com/Liath/aws-agent/commit/55ed9fa023b96b60bd1c2d3641ad6b60997370de
[0.0.5]: https://github.com/Liath/aws-agent/commit/08f4c086f5d2b33c9370602f80f7fb078d5f6a52
[0.0.4]: https://github.com/Liath/aws-agent/commit/dc04ca00eaafb992bdf04d7670482ffa2892c4ac
[0.0.3]: https://github.com/Liath/aws-agent/commit/dc04ca00eaafb992bdf04d7670482ffa2892c4ac
[0.0.2]: https://github.com/Liath/aws-agent/commit/dc04ca00eaafb992bdf04d7670482ffa2892c4ac
[0.0.1]: https://github.com/Liath/aws-agent/commit/8f834c25adf04cfb5fcb0f956b83eb6c216086a5