# Changelog

## [Unreleased][]

[Unreleased]: https://github.com/chaostoolkit/chaostoolkit-dynatrace/compare/0.1.0...HEAD

### Added

* Probes to query metris v2 endpoint
* Add a control to send logs
* Correlate logs to traces from Open Telemtry if found
* Probes to query logs
* Using `black` as formatter of the code
* Brought handy makefile from other projects
* Requires now Python 3.7 in line with Chaos Toolkit
* Update github build

### Changed

* Switched to [httpx][] as HTTP client

[httpx]: https://www.python-httpx.org/

### Added

-   Initial release
-   Added package to get failure rate service from dynatrace tools