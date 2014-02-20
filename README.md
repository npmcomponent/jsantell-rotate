*This repository is a mirror of the [component](http://component.io) module [jsantell/rotate](http://github.com/jsantell/rotate). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/jsantell-rotate`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
rotate
====

UI component for CSS3 rotations for use with [component](https://github.com/component/component). Works in Chrome, Firefox, Opera, Safari, IE9+

## Installation

```
component install jsantell/rotate
```

## API

### rotate(el, deg)

`rotate` is just a function that takes an element and rotation value (in degrees) and rotates that element.

## Example

```js
var rotate = require('rotate');
var el = document.getElementById('someDiv');

rotate(el, 120); // rotate el by 120 degrees
```
