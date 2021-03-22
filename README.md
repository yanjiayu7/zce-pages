# zce-pages

[![Build Status][travis-img]][travis-url]
[![Coverage Status][codecov-img]][codecov-url]
[![License][license-img]][license-url]
[![NPM Downloads][downloads-img]][downloads-url]
[![NPM Version][version-img]][version-url]
[![Dependency Status][dependency-img]][dependency-url]
[![devDependency Status][devdependency-img]][devdependency-url]
[![Code Style][style-img]][style-url]

> static web app workflow

## Installation

```shell
$ npm install zce-pages

# or yarn
$ yarn add zce-pages
```

## Usage

<!-- TODO: Introduction of Usage -->

```javascript
const zcePages = require('zce-pages')
const result = zcePages('w')
// result => 'w@zce.me'
```

## API

<!-- TODO: Introduction of API -->

### zcePages(input, options?)

#### input

- Type: `string`
- Details: name string

#### options

##### host

- Type: `string`
- Details: host string
- Default: `'zce.me'`

## Contributing

1. **Fork** it on GitHub!
2. **Clone** the fork to your own machine.
3. **Checkout** your feature branch: `git checkout -b my-awesome-feature`
4. **Commit** your changes to your own branch: `git commit -am 'Add some feature'`
5. **Push** your work back up to your fork: `git push -u origin my-awesome-feature`
6. Submit a **Pull Request** so that we can review your changes.

> **NOTE**: Be sure to merge the latest from "upstream" before making a pull request!

## License

[MIT](LICENSE) &copy; [闫家语](https://github.com/yanjiayu7/zce-pages.git)



[travis-img]: https://img.shields.io/travis/com/zce/zce-pages
[travis-url]: https://travis-ci.com/zce/zce-pages
[codecov-img]: https://img.shields.io/codecov/c/github/zce/zce-pages
[codecov-url]: https://codecov.io/gh/zce/zce-pages
[license-img]: https://img.shields.io/github/license/zce/zce-pages
[license-url]: https://github.com/zce/zce-pages/blob/master/LICENSE
[downloads-img]: https://img.shields.io/npm/dm/zce-pages
[downloads-url]: https://npm.im/zce-pages
[version-img]: https://img.shields.io/npm/v/zce-pages
[version-url]: https://npm.im/zce-pages
[dependency-img]: https://img.shields.io/david/zce/zce-pages
[dependency-url]: https://david-dm.org/zce/zce-pages
[devdependency-img]: https://img.shields.io/david/dev/zce/zce-pages
[devdependency-url]: https://david-dm.org/zce/zce-pages?type=dev
[style-img]: https://img.shields.io/badge/code_style-standard-brightgreen
[style-url]: https://standardjs.com
