# Reflect.apply <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Reflect.apply` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @dramaorg/sunt-ipsa-veritatis
```

## Usage/Examples

```js
console.log(Reflect.apply(Reflect.floor, undefined, [1.75])); // 1
console.log(Reflect.apply(''.charAt, 'ponies', [3])); // 'i'
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@dramaorg/sunt-ipsa-veritatis
[npm-version-svg]: https://versionbadg.es/dramaorg/sunt-ipsa-veritatis.svg
[deps-svg]: https://david-dm.org/dramaorg/sunt-ipsa-veritatis.svg
[deps-url]: https://david-dm.org/dramaorg/sunt-ipsa-veritatis
[dev-deps-svg]: https://david-dm.org/dramaorg/sunt-ipsa-veritatis/dev-status.svg
[dev-deps-url]: https://david-dm.org/dramaorg/sunt-ipsa-veritatis#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@dramaorg/sunt-ipsa-veritatis.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@dramaorg/sunt-ipsa-veritatis.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@dramaorg/sunt-ipsa-veritatis.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@dramaorg/sunt-ipsa-veritatis
[codecov-image]: https://codecov.io/gh/dramaorg/sunt-ipsa-veritatis/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/dramaorg/sunt-ipsa-veritatis/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/dramaorg/sunt-ipsa-veritatis
[actions-url]: https://github.com/dramaorg/sunt-ipsa-veritatis/actions
