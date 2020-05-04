# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.9.3] - 2020-05-04
### Changed
- Fixed return of rog-core in client mode
- Fixed writing of customised builtin LED modes

## [0.9.2] - 2020-05-04
### Added
- Begin keeping a Changelog

### Changed
- Internal structure changes to reduce the possibility of mutex await deadlocks when
  writing to the LED endpoint