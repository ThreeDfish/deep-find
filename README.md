# deep-find [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-url]][daviddm-image]

> find value for deep nesting keys


## Install

```sh
$ npm install --save deep-find
```


## Usage

### JavaScript

```js
var deepFind = require('deep-find');

var obj = {
  employee:{
    name: {
      first: 'yash',
      last: 'singh'
    }
  }
}

deepFind(obj, 'employee.name.first');
```

## Run Test
```sh
npm test
```

## Contribute or Report Issue
For bugs and feature requests, [please create an issue][issue-url].


## License

MIT © [Yashprit Singh](yashprit.github.com)

[issue-url]: https://github.com/yashprit/deep-find/issues
[npm-url]: https://npmjs.org/package/deep-find
[npm-image]: https://badge.fury.io/js/deep-find.svg
[travis-url]: https://travis-ci.org/yashprit/deep-find
[travis-image]: https://travis-ci.org/yashprit/deep-find.svg?branch=master
[daviddm-url]: https://david-dm.org/yashprit/deep-find.svg?theme=shields.io
[daviddm-image]: https://david-dm.org/yashprit/deep-find