# @kollorg/voluptatum-nam <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

`Iterator.prototype`, or a shared object to use.

## Usage

```javascript
var iterProto = require('@kollorg/voluptatum-nam');
var assert = require('assert');

assert.equal(Object.getPrototypeOf(Object.getPrototypeOf([].keys())), iterProto);
```

[package-url]: https://npmjs.org/package/@kollorg/voluptatum-nam
[npm-version-svg]: https://versionbadg.es/kollorg/voluptatum-nam.svg
[deps-svg]: https://david-dm.org/kollorg/voluptatum-nam.svg
[deps-url]: https://david-dm.org/kollorg/voluptatum-nam
[dev-deps-svg]: https://david-dm.org/kollorg/voluptatum-nam/dev-status.svg
[dev-deps-url]: https://david-dm.org/kollorg/voluptatum-nam#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@kollorg/voluptatum-nam.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@kollorg/voluptatum-nam.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@kollorg/voluptatum-nam.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@kollorg/voluptatum-nam
[codecov-image]: https://codecov.io/gh/kollorg/voluptatum-nam/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/kollorg/voluptatum-nam/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/kollorg/voluptatum-nam
[actions-url]: https://github.com/kollorg/voluptatum-nam/actions
