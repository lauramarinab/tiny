# @lauramarinab/tiny

![npm (scoped)](https://img.shields.io/npm/v/@lauramarinab/tiny?style=flat-square)
![npm bundle size (scoped)](https://img.shields.io/bundlephobia/min/@lauramarinab/tiny?style=flat-square)

Removes all spaces from a string.

## Install

```
$ npm install @lauramarinab/tiny
```

## Usage

```js
const tiny = require("@lauramarinab/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
