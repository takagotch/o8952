### wif
---
https://github.com/bitcoinjs/wif

```js
var wif = require('wif')
var privateKey = new Buffer('xxxx', 'hex')
var key = wif.encode(128, privateKey, true)

var obj = wif.decode(key)

wif.decode(key, 0x09)

wif.encode(obj)
```

```
```


```
```

