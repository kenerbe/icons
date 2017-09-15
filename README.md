# icons

# TOC
   - [A suite of sequential tests](#a-suite-of-sequential-tests)
<a name=""></a>
 
<a name="a-suite-of-sequential-tests"></a>

![Redis](https://github.com/kenerbe/icons/blob/master/src/Redis.png)

# A suite of sequential tests
- test #1 should take about 100ms.

```js
expect(foo).to.be.a('string')
setTimeout(done, 100)
```

- test #2 should take about 200ms.

```js
expect(foo).to.equal('bar')
setTimeout(done, 200)
```

- test #3 should take about 300ms.

```js
expect(foo).to.have.lengthOf(3)
setTimeout(done, 300)
```

- test #4 should take about 400ms.

```js
expect(beverages).to.have.property('beer').with.lengthOf(3)
setTimeout(done, 400)
```

- test #5 should take about 500ms.

```js
expect(beverages.beer[2]).to.equal('SilurianStout')
setTimeout(done, 500)
```


> Written with [StackEdit](https://stackedit.io/).
