# Changelog 
All notable changes to this project will be documented in this file. 
 
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), 
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html). 
 
## [Unreleased]
### Fixed
* Removed unneeded serializer from requirements.

### Added
* Explore response from HW will define connectivity based on working modules.
* Health check monitor.
* Error reporting - Clocks, temperature, FPGA, etc.
* Overheat protection will disable modules if passing 65 deg.
* Reset function - will release protection and reset octave HW state

## [1.0.1]
First official release.

## [1.0.0] 
### Fixed
* Disabled MODE_INTERNAL_USE_1G.
* Fixed set_clock edge cases, 1GHz external will use buffered state instead.

### Added 
* Loopback Support.

### Fixed 
* set gain works for all gain range.

## [0.0.1] 
### Added 
* Initial SDK code.

[Unreleased]: https://github.com/qm-labs/opmix/compare/v...HEAD
[1.0.1]: https://github.com/qm-labs/opmix/releases/tag/v