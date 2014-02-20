*This repository is a mirror of the [component](http://component.io) module [forbeslindesay/curry](http://github.com/forbeslindesay/curry). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/forbeslindesay-curry`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
<a href="https://jepso-ci.com/ForbesLindesay/curry"><img src="https://jepso-ci.com/ForbesLindesay/curry.svg" align="right" alt="jepso-ci status" /></a>
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

![viewcount](https://viewcount.jepso.com/count/ForbesLindesay/curry.png)
