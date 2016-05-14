##  npm

```js
// js/index.js

import Dropin from './dropin/main.js';

let dropin = new Dropin();

export var setup = dropin.setup; // punch.setup() from earlier!
export var destroyAll = dropin.destroyAll;
export var instances = dropin.instances;
```
