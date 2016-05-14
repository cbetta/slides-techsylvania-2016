## Redux

```sh
npm install redux
```

```js
// dropin.js
import './tags/punch-dropin.tag';

import riot from 'riot';
import { createStore } from 'redux';
import StoreMixin      from 'riot-redux-mixin';

let state = ...
let store = createStore(state);
riot.mixin('redux', new StoreMixin(store));

riot.mount('#element', "punch-dropin");
```
