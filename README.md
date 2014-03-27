# unique-words [![NPM version](https://badge.fury.io/js/unique-words.png)](http://badge.fury.io/js/unique-words)

> Return the unique words in a string or array.

See the [performance tests](http://jsperf.com/unique-words);

## Install
Install with [npm](npmjs.org):

```bash
npm i unique-words --save-dev
```

## Usage
```js
var unique = require('unique-words');
var str = 'one two one two three';

console.log(unique(str));
// => ['one', 'two', 'three']

var arr = [
  'foo',
  'foo',
  'foo bar',
  'bar',
  'bar baz foo'
];

console.log(unique(arr));
// => ['foo', 'bar', 'baz']
```


## Tests

Run the tests with

```bash
mocha -R spec
```

## Author

**Jon Schlinkert**

+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License
Copyright (c) 2014 Jon Schlinkert, contributors.  
Released under the MIT license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on March 27, 2014._