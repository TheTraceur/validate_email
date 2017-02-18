[![npm version](https://badge.fury.io/js/validate_email.svg)](https://www.npmjs.com/package/validate_email)

[![GitHub version](https://badge.fury.io/gh/TheTraceur%2Fvalidate_email.svg)](https://github.com/TheTraceur/validate_email)

![Awesome](http://cdn.pspu.pl/badges/awesome.svg)

© by [**traceur**](https://www.npmjs.com/~traceur)

## Installation

```bash
npm install -g validate_email
```

## Usage

```js
var validate_email = require( "validate_email" );

validate_email( "test@email.com" ); // true

validate_email( "im_not_an_email" ); // false
```