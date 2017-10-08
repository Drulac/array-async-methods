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

### usage
install
```
npm i array-async-methods
```
just require in your code the module
```js
require('array-async-methods');
```

### chainability
These methods are also usable on Promise, it's chainable :
```js
filesPath.mapA(filePath=>fsPromised.readFile(filePath,'utf8'))
.someA(async fileContent=>fileContent === 'good', '')
```