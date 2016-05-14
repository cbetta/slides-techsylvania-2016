##  Rollup UMD

```js
(function (global, factory) {
	typeof exports === 'object' && typeof module !== 'undefined' ? factory() :
	typeof define === 'function' && define.amd ? define(factory) :
	(factory());
}(this, function () { 'use strict';
	function cube ( x ) {
		return x * x * x;
	}

	console.log( cube( 5 ) );
}));
```
