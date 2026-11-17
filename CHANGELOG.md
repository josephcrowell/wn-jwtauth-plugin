# Changelog

## [3.0.0](https://github.com/josephcrowell/wn-jwtauth-plugin/compare/v2.0.2...v3.0.0) (2026-11-17)


### ⚠ BREAKING CHANGES

* error responses now use structured format {"error":{"code":"...","message":"..."}} across all endpoints. POST /account-activation now returns {"token","user"} instead of empty body (auto-login after activation).

### Features

* release v2.0.0 with structured errors and rate limiting ([951cc00](https://github.com/josephcrowell/wn-jwtauth-plugin/commit/951cc0075b731a4726ca47abc6b21d0f56fb63b8))
* upgrade plugin to WinterCMS 1.2/1.3 and PHP 8.1+ ([23379c7](https://github.com/josephcrowell/wn-jwtauth-plugin/commit/23379c73853571b7e1fc4813cf0799dcf8a25f65))


### Bug Fixes

* add missing Event facade import to RegisterController ([3ff0d73](https://github.com/josephcrowell/wn-jwtauth-plugin/commit/3ff0d73023e807f3ebf97fdee1dff8c10963d9cb))
* make RateLimitTest::setUp() public to match parent TestCase ([0ad838f](https://github.com/josephcrowell/wn-jwtauth-plugin/commit/0ad838fd6d2d7056283261b529e2d714d091d303))
* replaced tymon/jwt-auth with php-open-source-saver/jwt-auth ([55cafd3](https://github.com/josephcrowell/wn-jwtauth-plugin/commit/55cafd3b928066ba89240c8a8c24fb13cfd2b663))
* return JSON for jwt.auth middleware 401s on Winter ([56dba11](https://github.com/josephcrowell/wn-jwtauth-plugin/commit/56dba112ddc19f980d268000362ac78aa588c452))
* send JSON errors and Retry-After on Winter ([2ba9cde](https://github.com/josephcrowell/wn-jwtauth-plugin/commit/2ba9cde9e3f08b566b9a248daaa5bfca4fc2c293))
* update compose.json to allow composer/installers ([98196ce](https://github.com/josephcrowell/wn-jwtauth-plugin/commit/98196cee01594d5ec6db2e73095ba34c6423c7a1))

## [2.0.2](https://github.com/rluders/wn-jwtauth-plugin/compare/v2.0.1...v2.0.2) (2026-05-24)


### Bug Fixes

* add missing Event facade import to RegisterController ([3ff0d73](https://github.com/rluders/wn-jwtauth-plugin/commit/3ff0d73023e807f3ebf97fdee1dff8c10963d9cb))

## [2.0.1](https://github.com/rluders/wn-jwtauth-plugin/compare/v2.0.0...v2.0.1) (2026-05-24)


### Bug Fixes

* make RateLimitTest::setUp() public to match parent TestCase ([0ad838f](https://github.com/rluders/wn-jwtauth-plugin/commit/0ad838fd6d2d7056283261b529e2d714d091d303))

## [2.0.0](https://github.com/rluders/wn-jwtauth-plugin/compare/v1.5.0...v2.0.0) (2026-05-24)


### ⚠ BREAKING CHANGES

* error responses now use structured format {"error":{"code":"...","message":"..."}} across all endpoints. POST /account-activation now returns {"token","user"} instead of empty body (auto-login after activation).

### Features

* release v2.0.0 with structured errors and rate limiting ([951cc00](https://github.com/rluders/wn-jwtauth-plugin/commit/951cc0075b731a4726ca47abc6b21d0f56fb63b8))
* upgrade plugin to WinterCMS 1.2/1.3 and PHP 8.1+ ([23379c7](https://github.com/rluders/wn-jwtauth-plugin/commit/23379c73853571b7e1fc4813cf0799dcf8a25f65))
