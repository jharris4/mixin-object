# mixin-object [![NPM version](https://badge.fury.io/js/mixin-object.svg)](http://badge.fury.io/js/mixin-object)


> Add the properties from any number of objects into the first object. To create a new object pass an empty object as the first arg.

## Install
#### Install with [npm](npmjs.org):

```bash
npm i mixin-object --save-dev
```

## Run tests

```bash
npm test
```

## Usage

```js
var mixin = require('mixin-object');

var o = {c: 'c'};
mixin({}, {a: 'a'}, {b: 'b'});
//=> {a: 'a', b: 'b'}

mixin({}, {a: 'a'}, {b: 'b'});
//=> {a: 'a', b: 'b'}
```

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2014 Jon Schlinkert, contributors.  
Released under the MIT license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on September 22, 2014._