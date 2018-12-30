# tiny

[![](https://img.shields.io/npm/v/@0xsuid/tiny.svg)](https://github.com/0xsuid/tiny)
[![](https://img.shields.io/bundlephobia/min/@0xsuid/tiny.svg)](https://www.npmjs.com/package/@0xsuid/tiny)


Removes all spaces from a string.

## Install

``` 
npm install @0xsuid/tiny 
```

## Usage

```js
const tiny = require("@0xsuid/tiny");

tiny("So much space.");
// => Somuchspace

tiny(1337);
// => Uncaught error: Tiny wants a string
//      at tiny (<anonymous>2:41)
//      at <anonymous>1:1
```