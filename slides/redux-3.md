## Redux

```html
<!-- punch-dropin.tag -->
<punch-dropin>
  <h1>Counter: { state.count }</h1>

  <script type="text/javascript">
    this.mixin('redux');

    this.subscribe(function(state){
      this.state = state;
    }.bind(this))
  </script>
</punch-dropin>
```
