# Watch
[nodejs] Watch file changes.

### Install
```
npm install kc-watch
```

### Use
```js
var watch = require('kc-watch');
watch('.', function(d, f, e){
    if (f.match(/\.js$/)) {
        console.log(d, f, e);
    }
});
```
