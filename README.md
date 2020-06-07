# @aman_manocha_/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@aman_manocha_/tiny.svg)](https://www.npmjs.com/package/@aman_manocha_/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @aman_manocha_/tiny
```

## Usage

```js
const tiny = require("@aman_manocha_/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
