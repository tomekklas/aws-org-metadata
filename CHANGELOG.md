# Changelog

All notable changes to this project will be documented in this file.

## [1.0.2] - 2023-11-12

### Added

- **Enhanced Documentation**: Updated README.md to provide comprehensive details on response messages and data formats for better user understanding.
- **API Endpoint Refinement**: Modified the API endpoint from aws-org-metadata/account/{account_id} to aws-org-metadata/account_id/{account_id} for improved clarity and consistency in URL naming conventions.

### Fixed

- **Consistent No-Result Responses**: Standardized the response format for scenarios where no results are found. This ensures uniformity and predictability in API responses, enhancing the overall user experience and ease of handling different response scenarios programmatically.



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
