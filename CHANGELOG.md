# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [0.2.0] - 2019-04-26
### Changed
 - `actix-web` dependency is used without default features now ([#6](https://github.com/svartalf/actix-web-httpauth/pull/6))
 - `base64` dependency version was bumped to `0.10`

## [0.1.0] - 2018-09-08
### Changed
 - Update to `actix-web = "0.7"` version

## [0.0.4] - 2018-07-01
### Fixed
 - Fix possible panic at `IntoHeaderValue` implementation for `headers::authorization::Basic`
 - Fix possible panic at `headers::www_authenticate::challenge::bearer::Bearer::to_bytes` call
