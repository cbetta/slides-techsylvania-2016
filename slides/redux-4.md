## Redux

```js
// dropin.js

let state = function counter(count = 0, action) {
  switch (action) {
  case 'increment':
    return count + 1
  case 'decrement':
    return count - 1
  default:
    return count
}
```
