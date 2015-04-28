# random-iterate

Iterate values in a list in random order

```
npm install random-iterate
```

## Usage

``` js
var iterate = require('random-iterate')
var ite = iterate([1,2,3,4,5,6,7,8,9])

console.log(ite()) // maybe 4
console.log(ite()) // maybe 9
... 7 more time ...
console.log(ite()) // returns null (end of list)
```

## License

MIT
