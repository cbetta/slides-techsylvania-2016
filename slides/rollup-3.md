##  Rollup Tree Shaking

```js
// main.js
import { cube } from './maths.js';
console.log( cube( 5 ) );
```

```js
// maths.js

// unused function
export function square ( x ) {
	return x * x;
}

// included function
export function cube ( x ) {
	return x * x * x;
}
```
