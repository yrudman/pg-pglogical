# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) 
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## [2.1.1] - 2017-11-14
### Fixed
- Add the options parameter to the prepended drop table method [[#16](https://github.com/ManageIQ/pg-pglogical/pull/16)]

## [2.1.0] - 2017-11-13
### Added
- Prepend to activerecord's drop table method for removing the table from replication sets [[#14](https://github.com/ManageIQ/pg-pglogical/pull/14)]

## [2.0.0] - 2017-10-11
### Changed
- Alter definitions for pglogical 2.0+ compatibility [[#12](https://github.com/ManageIQ/pg-pglogical/pull/12)]

## [1.1.0] - 2017-02-27
### Added
- Add the remote and local lsn to the subscription status [[#8](https://github.com/ManageIQ/pg-pglogical/pull/8)]

[Unreleased]: https://github.com/ManageIQ/pg-pglogical/compare/v2.0.0...HEAD
[2.0.0]: https://github.com/ManageIQ/pg-pglogical/compare/v1.1.0...v2.0.0
[1.1.0]: https://github.com/ManageIQ/pg-pglogical/compare/v1.0.0...v1.1.0
