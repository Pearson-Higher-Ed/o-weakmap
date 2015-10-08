# o-weakmap

[WeakMap](http://www.ecma-international.org/ecma-262/6.0/#sec-weakmap-objects) ponyfill.

**This component is deprecated**. Component bundles that are built using the latest version of [origami-build-tools](https://github.com/Financial-Times/origami-build-tools) include the Babel [runtime](https://babeljs.io/docs/usage/runtime/), which polyfills ES2015 built-ins, such as `Promise`, `Map`, `Set`, and `WeakMap`.

## Usage

```js
var WeakMap = require('o-weakmap');
var wm = new WeakMap();
var o = function () {};

wm.set(o, 'foo');
wm.get(o);        // Foo
wm.has(o);        // true
```

## License

This software includes code from [webcomponents/webcomponentsjs](https://github.com/webcomponents/webcomponentsjs) that is published under the BSD style license. Copyright (c) 2015 The Polymer Authors. All rights reserved.
