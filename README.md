# @webstandardcss/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@webstandardcss/tiny.svg)](https://www.npmjs.com/package/@webstandardcss/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@webstandardcss/tiny.svg)](https://www.npmjs.com/package/@webstandardcss/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @webstandardcss/tiny
```

## Usage

```js
const tiny = require("@webstandardcss/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
Credits to: https://medium.freecodecamp.org/how-to-make-a-beautiful-tiny-npm-package-and-publish-it-2881d4307f78
