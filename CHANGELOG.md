# Changelog

All notable changes to this project will be documented in this file.

## [1.0.1] - 2023-11-09

### Added
- Updated README.md with more detailed CLI deployment examples
- FetchAccountIdsLambdaName output to data-source.yaml

### Fixed
- Resolved race condition issue between stage deployment and API Key creation
- Renamed Params in data-source.yaml and master-role.yaml to keep them consistient between templates

## [1.0] - 2023-11-02

### Added
- Initial working version of master-role.yaml
- Initial working version of data-source.yaml
- Initial working version of api-gateway.yaml
- Initial working version of README.md
