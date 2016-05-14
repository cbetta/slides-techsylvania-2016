## Redux

```html
<!-- punch-dropin.tag -->
<punch-dropin>
  <h1 onClick={ increment }>Counter: { state.count }</h1>

  <script type="text/javascript">
    this.mixin('redux');

    this.increment = function() {
      this.store.dispatch('increment');
    }
    
    this.subscribe(function(state){
      this.state = state;
    }.bind(this))
  </script>
</punch-dropin>
```
