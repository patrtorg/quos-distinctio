# @patrtorg/quos-distinctio <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@patrtorg/quos-distinctio');
const Eval = require('@patrtorg/quos-distinctio/eval');
const Range = require('@patrtorg/quos-distinctio/range');
const Ref = require('@patrtorg/quos-distinctio/ref');
const Syntax = require('@patrtorg/quos-distinctio/syntax');
const Type = require('@patrtorg/quos-distinctio/type');
const URI = require('@patrtorg/quos-distinctio/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@patrtorg/quos-distinctio
[npm-version-svg]: https://versionbadg.es/ljharb/@patrtorg/quos-distinctio.svg
[deps-svg]: https://david-dm.org/ljharb/@patrtorg/quos-distinctio.svg
[deps-url]: https://david-dm.org/ljharb/@patrtorg/quos-distinctio
[dev-deps-svg]: https://david-dm.org/ljharb/@patrtorg/quos-distinctio/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@patrtorg/quos-distinctio#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@patrtorg/quos-distinctio.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@patrtorg/quos-distinctio.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@patrtorg/quos-distinctio.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@patrtorg/quos-distinctio
[codecov-image]: https://codecov.io/gh/ljharb/@patrtorg/quos-distinctio/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@patrtorg/quos-distinctio/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@patrtorg/quos-distinctio
[actions-url]: https://github.com/patrtorg/quos-distinctio/actions
