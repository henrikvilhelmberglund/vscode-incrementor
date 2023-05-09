# Changelog

All notable changes to this project will be documented in this file. See [commit-and-tag-version](https://github.com/absolute-version/commit-and-tag-version) for commit guidelines.

## [2.4.1](https://github.com/henrikvilhelmberglund/vscode-incrementor/compare/v2.4.0...v2.4.1) (2023-05-09)


### Bug Fixes

* :bug: revert package.json pattern for now ([06644a5](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/06644a5ccd0db647a77d9048373659863e4e132c))

## [2.4.0](https://github.com/henrikvilhelmberglund/vscode-incrementor/compare/v2.3.0...v2.4.0) (2023-05-08)


### Features

* :page_facing_up: add license (keeps complaining when publishing) ([bc39bc9](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/bc39bc9ffeb6f2e0b7ecb49afefbf46b435d2c6d))


### Bug Fixes

* :bug: update regex pattern in the package.json for vscode to stop complaining when using forward slashes ([221dedf](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/221dedf4fc0ad60b0384677d3750195335ba57f9))

## [2.3.0](https://github.com/henrikvilhelmberglund/vscode-incrementor/compare/v2.2.0...v2.3.0) (2023-05-08)


### Features

* :sparkles: add forward slash to bounds ([1eabb09](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/1eabb099179d761cf66e506a1c837b183641ec97))

## [2.2.0](https://github.com/henrikvilhelmberglund/vscode-incrementor/compare/v2.1.2...v2.2.0) (2023-05-08)


### Features

* :sparkles: add / regex matching ([374514b](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/374514be14328bb46ddc5ffc11ad40eb60dd1b9d))


### Bug Fixes

* :bug: fix node 18 jank ([c51f32b](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/c51f32bf3ef077dffda429f0a5210e4bb54644cd))

## [2.1.2](https://github.com/henrikvilhelmberglund/vscode-incrementor/compare/v2.1.1...v2.1.2) (2023-01-20)


### Bug Fixes

* :fire: remove dot from wordrange bounds ([762f713](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/762f7137cfcf2c691823044cff6bf284b67ddf8d))

## [2.1.1](https://github.com/henrikvilhelmberglund/vscode-incrementor/compare/v2.1.0...v2.1.1) (2023-01-20)


### Bug Fixes

* :bug: adjust enum before number ([c30deb0](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/c30deb0995b049e0f57d6c0472a79e72232beeb5))

## [2.1.0](https://github.com/henrikvilhelmberglund/vscode-incrementor/compare/v2.0.0...v2.1.0) (2023-01-20)


### Features

* :sparkles: add workaround in README.md ([df58bd6](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/df58bd63a86e8aea4fda35f38be221de05457579))


### Bug Fixes

* :fire: remove preprod, didn't work there, but run that command before prod ([dbbe2e7](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/dbbe2e7891d91e19d74d6d17cdc55aaf46ad2bce))

## 2.0.0 (2023-01-20)


### ⚠ BREAKING CHANGES

* All of the settings were changed. The old settings are now deprecated.

### Features

* :memo: edit README ([8a30ac2](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/8a30ac2c19877a298035d575c285b2804348afa3))
* :sparkles: add preprod to fix error, change package.json details ([7e5014b](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/7e5014bb3058eeb3fbf69a603ab17da7dc13b21b))
* :sparkles: change name ([83fbf40](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/83fbf40c9b29389ea02f5680edd563ca693a68a2))
* :sparkles: set hash function (not sure if needed) ([8529b7a](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/8529b7a32864bbc1fa129662896a006129469db1))


### Bug Fixes

* **debug:** fix incorrect extension name in debug logging ([3eccdc8](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/3eccdc8536920e64927a5d34f7015d2da5d33ead))
* fix conflict with deprecated options ([2794341](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/2794341f50409e4882df2d54c65c7c0f554469a7))


* rewrite whole extension ([6dbfb18](https://github.com/henrikvilhelmberglund/vscode-incrementor/commit/6dbfb181ebc9629d3f5ae46bd45b7fde5cea3516))

### [1.0.3](https://github.com/nmsmith22389/vscode-incrementor/compare/v1.0.2...v1.0.3) (2020-08-31)

### [1.0.2](https://github.com/nmsmith22389/vscode-incrementor/compare/v1.0.1...v1.0.2) (2020-08-25)


### Bug Fixes

* fix conflict with deprecated options ([2794341](https://github.com/nmsmith22389/vscode-incrementor/commit/2794341f50409e4882df2d54c65c7c0f554469a7))

### [1.0.1](https://github.com/nmsmith22389/vscode-incrementor/compare/v1.0.0...v1.0.1) (2020-08-19)

## 1.0.0 (2020-08-19)


### ⚠ BREAKING CHANGES

* All of the settings were changed. The old settings are now deprecated.

### Bug Fixes

* **debug:** fix incorrect extension name in debug logging ([3eccdc8](https://github.com/nmsmith22389/vscode-incrementor/commit/3eccdc8536920e64927a5d34f7015d2da5d33ead))


* rewrite whole extension ([6dbfb18](https://github.com/nmsmith22389/vscode-incrementor/commit/6dbfb181ebc9629d3f5ae46bd45b7fde5cea3516))

## 0.0.1 (2017-02-14)
- Initial release
