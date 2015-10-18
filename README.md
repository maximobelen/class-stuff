# class-stuff

[![stable](http://badges.github.io/stability-badges/dist/stable.svg)](http://github.com/badges/stability-badges)

A javascript module with: addClass, removeClass and hasClass methods

```js
var classStuff = require('class-stuff');

var alertField = document.getElementById('alert-field');

classStuff.removeClass(alertField, 'alert-danger');
classStuff.addClass(alertField, 'alert-success' );
classStuff.hasClass(alertField, '.alert-info' ); // false

```
## Usage

[![NPM](https://nodei.co/npm/class-stuff.png)](https://www.npmjs.com/package/class-stuff)
