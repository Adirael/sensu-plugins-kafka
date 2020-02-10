#Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## [Unreleased]

### Breaking Changes
- Bump `sensu-plugin` dependency from `~> 2.7` to `~> 4.0` you can read the changelog entries for [4.0](https://github.com/sensu-plugins/sensu-plugin/blob/master/CHANGELOG.md#400---2018-02-17), [3.0](https://github.com/sensu-plugins/sensu-plugin/blob/master/CHANGELOG.md#300---2018-12-04), and [2.0](https://github.com/sensu-plugins/sensu-plugin/blob/master/CHANGELOG.md#v200---2017-03-29)

### Added
- Travis build automation to generate Sensu Asset tarballs that can be used n conjunction with Sensu provided ruby runtime assets and the Bonsai Asset Index
- Require latest sensu-plugin for [Sensu Go support](https://github.com/sensu-plugins/sensu-plugin#sensu-go-enablement)

### Fixed
### Changed

## [0.11.0] - 2017-02-17

### Added
- check-consumer-lag: threshold per partition

## [0.10.0] - 2017-02-16

### Added
- check-topic.rb: check isr

## [0.9.1] - 2017-02-16

### Fixed
- add missing methods

## [0.9.0] - 2017-02-16

### Breaking Changes
- Refactoring metrics-consumer-lag to remove shell/jvm execution

## [0.8.1] - 2017-02-16

### Fixed
- check-consumer-lag: remove celluloid (temporary), fix data structure, fix partition_owner function

## [0.8.0] - 2017-02-15

### Breaking Changes
- Refactoring check-consumer-lag to remove shell/jvm execution

## [0.7.0] - 2017-02-10

### Added
- Add option to check topic's replicas

## [0.6.1] - 2017-02-10

### Fixed
- Fix check-topics-name.rb

## [0.6.0] - 2017-02-10

### Added
- Add check-topics-name.rb

## [0.5.1] - 2017-02-10

### Fixed
- Add option to check topic's leader

## [0.5.0] - 2017-02-09

### Added
- Add option to check topic's leader

## [0.4.0] - 2017-02-09

### Added
- Add option to check topic's config

## [0.3.0] - 2017-02-09

### Added
- check-topic.rb: option to check partitions and replication factor

## [0.2.0] - 2017-02-09

### Breaking Changes
- check-topics.rb has been removed

### Added
- Add check-topic.rb

## [0.1.1] - 2017-02-04

### Fixed
- Ruby doc

## [0.1.0] - 2017-02-04
- First release