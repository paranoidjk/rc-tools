# rmc-tools

offline tools for react component

[![NPM version][npm-image]][npm-url]
[![gemnasium deps][gemnasium-image]][gemnasium-url]
[![node version][node-image]][node-url]
[![npm download][download-image]][download-url]

[npm-image]: http://img.shields.io/npm/v/rmc-tools.svg?style=flat-square
[npm-url]: http://npmjs.org/package/rmc-tools
[travis-image]: https://img.shields.io/travis/paranoidjk/rmc-tools.svg?style=flat-square
[travis-url]: https://travis-ci.org/paranoidjk/rmc-tools
[coveralls-image]: https://img.shields.io/coveralls/paranoidjk/rmc-tools.svg?style=flat-square
[coveralls-url]: https://coveralls.io/r/paranoidjk/rmc-tools?branch=master
[gemnasium-image]: http://img.shields.io/gemnasium/paranoidjk/rmc-tools.svg?style=flat-square
[gemnasium-url]: https://gemnasium.com/paranoidjk/rmc-tools
[node-image]: https://img.shields.io/badge/node.js-%3E=_0.11-green.svg?style=flat-square
[node-url]: http://nodejs.org/download/
[download-image]: https://img.shields.io/npm/dm/rmc-tools.svg?style=flat-square
[download-url]: https://npmjs.org/package/rmc-tools

## Usage

```
$ rmc-tools run lint: run lint by https://github.com/airbnb/javascript
$ rmc-tools run pub: compile and npm publish
$ rmc-tools run watch --out-dir=/xx: watch and compile to /xx, default to lib
$ rmc-tools run build: build examples
$ rmc-tools run gh-pages: push example to gh-pages
$ rmc-tools run start: start dev server
```

## preact


```
$ DEMO_ENV=preact rmc-tools run start:   start dev server with preact and preact-devtools auto inject
```

## standalone react-devtools

for simulator, safari, react-native debugger etc.


```
$ DEMO_ENV=debugger rmc-tools run start:  start dev server with a standalone react-devtools connected to your page
```

## package.json demo

```js
({
  config: {
    entry:{}, // webpack entry for build dist umd
    port: 8000, // dev server port
    output:{}, // webpack output for build dist umd
  }
})
```

## History

### 6.0.0

- move test to rc-test
