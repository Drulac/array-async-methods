# array-async-methods

### available methods

* mapA
* forEachA
* filterA
* reduceA
* reduceRightA
* everyA
* someA
* findA
* findIndexA

Provide promise instead of callback. That's return a Promise.

These methods are also usable on Promise, it's chainable :
```js
filesPath.mapA(filePath=>fsPromised.readFile(filePath,'utf8'))
.someA(async fileContent=>fileContent === 'good', '')
```