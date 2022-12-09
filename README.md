# @nverino/tiny

![npm (scoped)](https://img.shields.io/npm/v/@nverino/tiny)
![npm bundle size (scoped)](https://img.shields.io/bundlephobia/min/nverino/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @nverino/tiny
```

## Usage

```js
const tiny = require("@nverino/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
