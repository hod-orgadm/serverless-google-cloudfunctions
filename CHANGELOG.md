# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [3.0.0](https://github.com/serverless/serverless-google-cloudfunctions/compare/v2.4.3...v3.0.0) (2020-04-01)

### ⚠ BREAKING CHANGES

- Drop support for Node.js v6
- Services deployed with v1 Beta cannot be updated with v1.

Co-authored-by: Jeremy Minhua Bao (US - ADVS) <jeremy.bao@pwc.com>
Co-authored-by: zxhaaa <zxhaaa@hotmail.com>
Co-authored-by: Peachey_Chen <mr_robot2015@foxmail.com>

### Features

- Switch from CloudFunctions v1 beta to v1 ([#206](https://github.com/serverless/serverless-google-cloudfunctions/issues/206)) ([482ee0e](https://github.com/serverless/serverless-google-cloudfunctions/commit/482ee0e63a1f72dec8cce6c80dfe66ab406671ae))
- Upgrade googleapis to latest version ([#209](https://github.com/serverless/serverless-google-cloudfunctions/issues/209)) ([ab0d8ba](https://github.com/serverless/serverless-google-cloudfunctions/commit/ab0d8ba802d5999c9848232e836651c577a9f0cd))

### [2.4.3](https://github.com/serverless/serverless-google-cloudfunctions/compare/v2.4.2...v2.4.3) (2020-04-01)

### Bug Fixes

- Revert breaking switch from v1 beta to v1 CloudFunctions ([#207](https://github.com/serverless/serverless-google-cloudfunctions/issues/207)) ([fc1dbe2](https://github.com/serverless/serverless-google-cloudfunctions/commit/fc1dbe28be4b1dab0abe4216993c63c543e547eb))

### [2.4.2](https://github.com/serverless/serverless-google-cloudfunctions/compare/v2.4.1...v2.4.2) (2020-03-25)

- Ensure to rely internally on v1 and not v1 Beta CloudFunctions API ([#165](https://github.com/serverless/serverless-google-cloudfunctions/issues/165)) ([Eisuke Kuwahata](https://github.com/mather))

### [2.4.1](https://github.com/serverless/serverless-google-cloudfunctions/compare/v2.4.0...v2.4.1) (2020-02-28)

### Bug Fixes

- Bring back Node.js v6 support ([#197](https://github.com/serverless/serverless-google-cloudfunctions/issues/197)) ([f3b9881](https://github.com/serverless/serverless-google-cloudfunctions/commit/f3b9881086ff39416861c7b0549a4ded14fe7268)) ([Mariusz Nowak](https://github.com/medikoo))
- Fix handling of `maxInstances` setting ([#199](https://github.com/serverless/serverless-google-cloudfunctions/issues/199)) ([4ea8418](https://github.com/serverless/serverless-google-cloudfunctions/commit/4ea841879edf8605fe5b38668f6d1fb875347aae)) ([holmerjohn](https://github.com/holmerjohn))
