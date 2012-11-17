
# curry

  Curry a function in JavaScript

## Installation

    $ component install ForbesLindesay/curry

## API

```javascript
var curry = require('curry');

var sumFour = curry(function (a, b, c, d) {
  return a + b + c + d;
});

sumFour(5)(5)(5)(5);// => 20
sumFour(5, 5)(5, 5);// => 20
sumFour(5, 5, 5, 5);// => 20
sumFour(5)(5, 5, 5);// => 20
sumFour(5, 5, 5)(5);// => 20
```

## License

  MIT
