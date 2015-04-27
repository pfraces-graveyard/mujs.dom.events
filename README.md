domo.on.extras
==============

A collection of [domo plugins](https://github.com/domojs/domo) to deal
with events

Usage
-----

```js
var dom   = require('domo').use({
  onInput : require('domo.on.input')
});

var logName = function (name) {
  console.log('name:', name);
};

dom('#hero .name').onInput(logName);
```
