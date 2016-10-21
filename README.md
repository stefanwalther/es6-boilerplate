## What is es6-boilerplate

boilerplate-es6 is a template for your es6 based projects using

## Install

```
$ git clone git@github.com:stefanwalther/boilerplate-es6.git
```

## Basic concept

* JavaScript ES6
* ES6 Transpiler
  - [babel](https://babeljs.io/)
* Build system
  - [gulp](http://gulpjs.com/)
* Test framework
  - [mocha](https://mochajs.org/)
  - [istanbul](https://istanbul.js.org/) & [nyc](https://github.com/istanbuljs/nyc)
* Code style
  - [idiomatic](https://github.com/rwaldron/idiomatic.js/)
  - [eslint](http://eslint.org/) (using JS code style idiomatic)
* Documentation
  - [verb](https://github.com/verbose/verb)

## Script Tasks

### build

> Build the code from `./src`, store in `./dist`

```sh
npm run build
```

### Test

```sh
## Unit tests
npm run test:unit

## E2E tests
npm run test:e2e

## All tests
npm run test
```

### Test coverage

```sh
npm run coverage
```

### Linting

```sh
## Lint `./src`
npm run lint

## Lint './test`
npm run lint:test
```

### Documentation

```sh
## Generated documentation using verb
npm run docs
```

## Author

**Stefan Walther**

* [github/stefanwalther](https://github.com/stefanwalther)
* [twitter/waltherstefan](http://twitter.com/waltherstefan)

## License

Released under the MIT license.

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.1.30, on October 21, 2016._