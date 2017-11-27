# atom-sorter

  [![NPM version][npm-image]][npm-url]
  [![build status][travis-image]][travis-url]
  [![Test coverage][codecov-image]][codecov-url]
  [![David deps][david-image]][david-url]
  [![npm download][download-image]][download-url]
  
Callback allowing to sort chemical elements (atoms) in Hill order

## Installation

`$ npm install atom-sorter`

## [API Documentation](https://cheminfo-js.github.io/atom-sorter/)

## Example

```js
const atomSorter = require('atom-sorter');

let atoms = ['H', 'Cl', 'C', 'O', 'N', 'Br'];
atoms.sort((a, b) => atomSorter(a, b));

// ['C', 'H', 'Br', 'Cl', 'N', 'O']

```


## License

[MIT](./LICENSE)

[npm-image]: https://img.shields.io/npm/v/atom-sorter.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/atom-sorter
[travis-image]: https://img.shields.io/travis/cheminfo-js/atom-sorter/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/cheminfo-js/atom-sorter
[codecov-image]: https://img.shields.io/codecov/c/github/cheminfo-js/atom-sorter.svg?style=flat-square
[codecov-url]: https://codecov.io/gh/cheminfo-js/atom-sorter
[david-image]: https://img.shields.io/david/cheminfo-js/atom-sorter.svg?style=flat-square
[david-url]: https://david-dm.org/cheminfo-js/atom-sorter
[download-image]: https://img.shields.io/npm/dm/atom-sorter.svg?style=flat-square
[download-url]: https://www.npmjs.com/package/atom-sorter
