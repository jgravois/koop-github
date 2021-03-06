# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [1.0.1] - 2015-08-13

### Changed
* Bump Esri Leaflet version used by preview to 1.0.0
* Switch from `mocha` to `tape` for tests

### Added
* Added `status.version` to provider exports

## [1.0.0] - 2015-07-28

### Added
* Now checking build status with Travis-CI
* Using [JavaScript Standard Style](https://github.com/feross/standard)

### Changed
* Improved documentation
* Moved from Esri to KoopJS github organization

### Removed
* Deleted unused fixtures and configuration files
* Removed broken TopoJSON support

### Fixed
* Reverted to leaflet CDN to fix broken `leaflet.css` link

## v0.1.12 - 2015-03-16

[1.0.1]: https://github.com/koopjs/koop-github/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/koopjs/koop-github/compare/v0.1.12...v1.0.0
