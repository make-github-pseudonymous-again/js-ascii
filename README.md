[js-ascii](http://make-github-pseudonymous-again.github.io/js-ascii)
==

ASCII code bricks for JavaScript.

[![License](https://img.shields.io/github/license/aureooms/js-ascii.svg?style=flat)](https://raw.githubusercontent.com/aureooms/js-ascii/master/LICENSE)
[![NPM version](https://img.shields.io/npm/v/@aureooms/js-ascii.svg?style=flat)](https://www.npmjs.org/package/@aureooms/js-ascii)
[![Bower version](https://img.shields.io/bower/v/@aureooms/js-ascii.svg?style=flat)](http://bower.io/search/?q=@aureooms/js-ascii)
[![Build Status](https://img.shields.io/travis/aureooms/js-ascii.svg?style=flat)](https://travis-ci.org/aureooms/js-ascii)
[![Coverage Status](https://img.shields.io/coveralls/aureooms/js-ascii.svg?style=flat)](https://coveralls.io/r/aureooms/js-ascii)
[![Dependencies Status](https://img.shields.io/david/aureooms/js-ascii.svg?style=flat)](https://david-dm.org/aureooms/js-ascii#info=dependencies)
[![devDependencies Status](https://img.shields.io/david/dev/aureooms/js-ascii.svg?style=flat)](https://david-dm.org/aureooms/js-ascii#info=devDependencies)
[![Code Climate](https://img.shields.io/codeclimate/github/aureooms/js-ascii.svg?style=flat)](https://codeclimate.com/github/aureooms/js-ascii)
[![NPM downloads per month](https://img.shields.io/npm/dm/@aureooms/js-ascii.svg?style=flat)](https://www.npmjs.org/package/@aureooms/js-ascii)
[![GitHub issues](https://img.shields.io/github/issues/aureooms/js-ascii.svg?style=flat)](https://github.com/aureooms/js-ascii/issues)
[![Inline docs](http://inch-ci.org/github/aureooms/js-ascii.svg?branch=master&style=shields)](http://inch-ci.org/github/aureooms/js-ascii)

## Installation

Can be managed through [duo](https://github.com/duojs/duo),
[component](https://github.com/componentjs/component),
[bower](https://github.com/bower/bower), or
[npm](https://github.com/npm/npm).

```js
let ascii = require( "@aureooms/js-ascii" ) ;
```

## Usage

```js
ascii.islower( 'a' ) ; // true
ascii.islower( 'à' ) ; // false
ascii.islower( 'A' ) ; // false
ascii.islower( 'À' ) ; // false
ascii.islower( '0' ) ; // false

ascii.isupper( 'a' ) ; // false
ascii.isupper( 'à' ) ; // false
ascii.isupper( 'A' ) ; // true
ascii.isupper( 'À' ) ; // false
ascii.isupper( '0' ) ; // false

ascii.isdigit( 'a' ) ; // false
ascii.isdigit( 'à' ) ; // false
ascii.isdigit( 'A' ) ; // false
ascii.isdigit( 'À' ) ; // false
ascii.isdigit( '0' ) ; // true
```
