##  npm

```js
// rollup/dist.js

export default {
  entry: 'js/index.js',
  dest: 'dist/punch.js',
  format: 'umd',
  moduleName: 'punch',
  plugins: [
    riot(),
    npm({ browser: true }),
    commonjs(),
    babel(),
    uglify()
  ]
};
```
