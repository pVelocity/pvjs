### ``createHash(str, len)``
Returns ``sha1`` hash hex string of ``str``.

- `str` `<String>`
- `len` `<Number>`: Optional, default is unlimited.

```js
var hash = PV.createHash('hello world', 13);
```