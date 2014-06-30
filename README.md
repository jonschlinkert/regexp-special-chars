# regexp-special-chars [![NPM version](https://badge.fury.io/js/regexp-special-chars.png)](http://badge.fury.io/js/regexp-special-chars)

> Special RegExp characters, useful for escaping.

## Install
Install with [npm](npmjs.org):

```bash
npm i regexp-special-chars --save-dev
```

## Usage

```js
var reChars = require('regexp-special-chars');
var esc = function(str) {
  return str.replace(reChars, '\\$&');
};
```

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2014 Jon Schlinkert, contributors.  
Released under the MIT license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on June 30, 2014._