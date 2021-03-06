# index-of [![NPM version](https://badge.fury.io/js/index-of.svg)](http://badge.fury.io/js/index-of)

> Get the index of the first element in an array that returns truthy for the given value, using strict equality for comparisons.

## Install

**Install with NPM**

Install with [npm](https://www.npmjs.com/)

```bash
npm i index-of --save
```

**Install with Bower**

Install with [bower](http://bower.io/)

```bash
bower install index-of --save
```

## Usage

```js
var indexOf = require('index-of');

indexOf(['a', 'b', 'c'], 'b');
//=> 1

indexOf(['a', 'b', 'c'], 'd');
//=> -1

indexOf(['a', 'b', 'c', 'a', 'b', 'c'], 'b', 2);
//=> 4
```

## Related projects

* [array-every](https://github.com/jonschlinkert/array-every): Returns true if the callback returns truthy for all elements in the given array.
* [array-slice](https://github.com/jonschlinkert/array-slice): Array-slice method. Slices `array` from the `start` index up to, but not including, the `end`… [more](https://github.com/jonschlinkert/array-slice)
* [array-unique](https://github.com/jonschlinkert/array-unique): Return an array free of duplicate values. Fastest ES5 implementation.
* [filter-array](https://github.com/jonschlinkert/filter-array): Iterates over the elements in an array, returning an array with only the elements for… [more](https://github.com/jonschlinkert/filter-array)
* [index-of](https://github.com/jonschlinkert/index-of): Get the index of the first element in an array that returns truthy for the… [more](https://github.com/jonschlinkert/index-of)

## Running tests

Install dev dependencies:

```bash
npm i -d && npm test
```

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/index-of/issues/new)

## Author

**Jon Schlinkert**

+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License

Copyright (c) 2015 Jon Schlinkert
Released under the MIT license.

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on May 07, 2015._