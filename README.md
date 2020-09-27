![Build](https://github.com/kasperhesthaven/gulp-ttf-to-woff2/workflows/NPM%20CD/badge.svg) ![Dependencies](https://img.shields.io/librariesio/release/npm/gulp-ttftowoff2) ![NPM Version](https://img.shields.io/npm/v/gulp-ttftowoff2)

# gulp-ttf-to-woff2

Gulp plugin to convert TTF(TrueType font) files to WOFF2 using [ttf2woff2](https://github.com/nfroidure/ttf2woff2).

## Install

`npm i gulp-ttftowoff2`

## Usage

```js
const gulp = require("gulp");
const ttfToWoff2 = require("gulp-ttftowoff2");

export function convertTffToWoff() {
  return gulp.src("./src/*.ttf").pipe(ttfToWoff2()).pipe(gulp.dest("./dist/"));
}
```
