# @xdanangelxoqenpm/iusto-nemo-expedita <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Returns an array of Typed Array names that are available in the current environment.

## Example

```js
var availableTypedArrays = require('@xdanangelxoqenpm/iusto-nemo-expedita');
var assert = require('assert');

assert.deepStrictEqual(
	availableTypedArrays().sort(),
	[
		'Int8Array',
		'Uint8Array',
		'Uint8ClampedArray',
		'Int16Array',
		'Uint16Array',
		'Int32Array',
		'Uint32Array',
		'Float32Array',
		'Float64Array',
		'BigInt64Array',
		'BigUint64Array'
	].sort()
);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@xdanangelxoqenpm/iusto-nemo-expedita
[2]: https://versionbadg.es/inspect-js/@xdanangelxoqenpm/iusto-nemo-expedita.svg
[5]: https://david-dm.org/inspect-js/@xdanangelxoqenpm/iusto-nemo-expedita.svg
[6]: https://david-dm.org/inspect-js/@xdanangelxoqenpm/iusto-nemo-expedita
[7]: https://david-dm.org/inspect-js/@xdanangelxoqenpm/iusto-nemo-expedita/dev-status.svg
[8]: https://david-dm.org/inspect-js/@xdanangelxoqenpm/iusto-nemo-expedita#info=devDependencies
[11]: https://nodei.co/npm/@xdanangelxoqenpm/iusto-nemo-expedita.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@xdanangelxoqenpm/iusto-nemo-expedita.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@xdanangelxoqenpm/iusto-nemo-expedita.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@xdanangelxoqenpm/iusto-nemo-expedita
[codecov-image]: https://codecov.io/gh/inspect-js/@xdanangelxoqenpm/iusto-nemo-expedita/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@xdanangelxoqenpm/iusto-nemo-expedita/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@xdanangelxoqenpm/iusto-nemo-expedita
[actions-url]: https://github.com/xdanangelxoqenpm/iusto-nemo-expedita/actions
