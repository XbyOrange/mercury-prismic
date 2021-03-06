# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [unreleased]
### Added
### Changed
### Fixed
### Removed
### BREAKING CHANGES

## [1.3.0] - 2019-10-23
### Added
- Change url configuration in runtime. Clean cache when url changes.

## [1.2.0] - 2019-10-15
### Added
- Add `url` property to config options.

### Changed
- Upgrade mercury version and define it as peer dependency
- Upgrade devDependencies

## [1.1.0] - 2019-06-28
### Changed
- Upgrade mercury version

## [1.0.0] - 2019-06-11
### BREAKING CHANGES
- Forked from xByOrange reactive-data-source v1.7.0 library. (Only origins.Prismic is exposed from now)
- Extends from Mercury Origin instead of reactive-data-source origin. (Refer to mercury CHANLEGOG for further details)
- Change constructor name from PrismicCMS to Prismic