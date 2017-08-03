### ``updateObjwithSameSchema(targeObj, sourceObj)``
Imprints the values of ``sourceObj`` onto ``targeObj``.

- `targeObj` `<Object>`
- `sourceObj` `<Object>`

```js
PV.updateObjwithSameSchema({
	a: 'bye'
}
}, {
	a: {
		b: {
			c: 'hello'
		}
	}
});
```