# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [4.1.0](https://github.com/adaltas/node-csv/compare/csv-generate@4.0.4...csv-generate@4.1.0) (2022-05-24)


### Features

* wg stream api ([8a5eb7d](https://github.com/adaltas/node-csv/commit/8a5eb7dfd31b22217db4fbbc832d707221850785))


### Bug Fixes

* **csv-generate:** catch invalid value error ([f031542](https://github.com/adaltas/node-csv/commit/f0315423ba576551f2bd08f3e1c3bc85e9003926))



## [4.0.4](https://github.com/adaltas/node-csv/compare/csv-generate@4.0.3...csv-generate@4.0.4) (2021-12-29)


### Bug Fixes

* correct exports in package.json with webpack ([154eafb](https://github.com/adaltas/node-csv/commit/154eafbac866eb4499a0d392f8dcd057695c2586))
* **csv-demo-webpack-ts:** remove polyfill ([47a99bd](https://github.com/adaltas/node-csv/commit/47a99bd944d1d943e6374227dbc4e20aaa2c8c7f))
* **csv-demo-webpack-ts:** simplify export paths ([8d63a14](https://github.com/adaltas/node-csv/commit/8d63a14313bb6b26f13fafb740cc686f1dfaa65f))
* esm exports in package.json files ([c48fe47](https://github.com/adaltas/node-csv/commit/c48fe478ced7560aa078fbc36ec33d6007111e2b)), closes [#308](https://github.com/adaltas/node-csv/issues/308)





## [4.0.3](https://github.com/adaltas/node-csv/compare/csv-generate@4.0.2...csv-generate@4.0.3) (2021-11-19)


### Bug Fixes

* expose browser esm modules ([eb87355](https://github.com/adaltas/node-csv/commit/eb873557c65912f065d2581d30a17a96b0bfd2d6))





## [4.0.2](https://github.com/adaltas/node-csv/compare/csv-generate@4.0.1...csv-generate@4.0.2) (2021-11-18)


### Bug Fixes

* dont insert polyfills in cjs [#303](https://github.com/adaltas/node-csv/issues/303) ([9baf334](https://github.com/adaltas/node-csv/commit/9baf334044dab90b4a0d096a7e456d0fd5807d5b))





## [4.0.1](https://github.com/adaltas/node-csv/compare/csv-generate@4.0.0...csv-generate@4.0.1) (2021-11-15)


### Bug Fixes

* remove samples from publicatgion ([12c221d](https://github.com/adaltas/node-csv/commit/12c221dc37add26f094e3bb7f94b50ee06ff5be6))





# [4.0.0](https://github.com/adaltas/node-csv/compare/csv-generate@3.4.3...csv-generate@4.0.0) (2021-11-15)


### Bug Fixes

* **csv-generate:** record emited after end with sleep ([6632e63](https://github.com/adaltas/node-csv/commit/6632e63a7aff7d33f47aae91347a39649d5248c6))
* **csv-generate:** stream.push after EOF ([97a3f58](https://github.com/adaltas/node-csv/commit/97a3f58dd73b6452b32cc39511b3ec145fe23c00))
* export original lib esm modules ([be25349](https://github.com/adaltas/node-csv/commit/be2534928ba21156e9cde1e15d2e8593d62ffe71))
* refer to esm files in dist ([b780fbd](https://github.com/adaltas/node-csv/commit/b780fbd26f5e54494e511eb2e004d3cdedee3593))


### Features

* backport support for node 14 ([dbfeb78](https://github.com/adaltas/node-csv/commit/dbfeb78f61ed36f02936d63a53345708ca213e45))
* backward support for node 8 ([496231d](https://github.com/adaltas/node-csv/commit/496231dfd838f0a6a72269a5a2390a4c637cef95))
* **csv-generate:** ts extends options with stream.ReadableOptions ([ef84fb2](https://github.com/adaltas/node-csv/commit/ef84fb2f980b5d39e2df2b61d012769119f31001))
* esm migration ([b5c0d4b](https://github.com/adaltas/node-csv/commit/b5c0d4b191c8b57397808c0922a3f08248506a9f))
* export ts types in sync ([890bf8d](https://github.com/adaltas/node-csv/commit/890bf8d950c18a05cab5e35a461d0847d9425156))
* replace ts types with typesVersions ([acb41d5](https://github.com/adaltas/node-csv/commit/acb41d5031669f2d582e40da1c80f5fd4738fee4))





## [3.4.2](https://github.com/adaltas/node-csv-generate/compare/csv-generate@3.4.1...csv-generate@3.4.2) (2021-08-27)

**Note:** Version bump only for package csv-generate





## 3.4.1 (2021-08-27)

**Note:** Version bump only for package csv-generate

## Version 3.4.0

* chore: integrate browserify

## Version 3.3.0

* package: latest dependencies
* package: mocha inside package declaration

## Version 3.2.4

* package: contributing
* package: code of conduct
* travis: remove node.js 8 and add 12
* src: minor code simplification
* package: update file path

## Version 3.2.3

* package: remove dot slash from files

## Version 3.2.2

* ts: place declaration files inside lib/es5 folder

## Version 3.2.1

* ts: declare options in typings as optional
* package: replace npm ignore with file field
* project: fix license in package.json
* babel: include .babelrc to git

## Version 3.2.0

* ts: new TypeScript definition files

## Version 3.1.0

* duration: fix start time
* package: MIT license (was BSD)
* sleep: new option

## Version 3.0.0

Breaking change:

* callback: generate buffers unless encoding is present

New features and bug fixes:

* options: accept snake case and came case keys
* eof: new option
* row_delimiter: new option
* travis: test against Node.js 11

## Version 2.2.2

* readme: fix website urls

## Version 2.2.1

* readme: fix links to project website

## Version 2.2.0

* package: move to csv.js.org
* package: upgrade dependencies including babel 7
* options: new duration option
* samples: new api sync scripts
* samples: new objectmode scripts
* readme: remove api doc
* travis: support Node.js 10
* samples: update syntax
* package: improve ignore files

## Version 2.1.0

* sync: new module to ease synchronous usage

## Version 2.0.2

* package: move babel to dev dependencies

## Version 2.0.1

* package: es5 backward compatiblity
* package: ignore yarn lock file

## 2.0.0

This major version use CoffeeScript 2 which produces a modern JavaScript syntax 
(ES6, or ES2015 and later) and break the compatibility with versions of Node.js 
lower than 7.6 as well as the browsers. It is however stable in term of API.

* package: use CoffeeScript 2

## v1.1.2

* tests: remove references to coverage

## v1.1.0

* test: should require handled by mocha
* package: coffeescript 2 and use semver tilde
* options: validate column types, fix #4
