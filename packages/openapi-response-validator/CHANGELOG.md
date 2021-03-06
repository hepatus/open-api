# openapi-response-validator Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 3.5.0 - 2018-12-20
### Fixed
- Making components arg optional and based on OpenAPIV3.ComponentsObject.

## 3.3.0 - 2018-12-12
### Fixed
- Handling application/json schemas for V3.

## 3.2.0 - 2018-12-11
### Fixed
- Handling nullable for V3

## 3.0.1 - 2018-10-03
### Fixed
- Updating .npmignore to publish `dist`

## 3.0.0 - 2018-10-02
### Added
- `export interface IOpenAPIResponseValidator`
- `export interface OpenAPIResponseValidatorArgs`
- `export interface OpenAPIResponseValidatorError`
- `export interface OpenAPIResponseValidatorValidationError`

### Fixed
- Upgraded ajv to `^6.5.4`

### Changed
- `module.exports` to `export default`
- Removed `status` from validation errors.
