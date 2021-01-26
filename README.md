# Shared-Common

A common functionalities shared between different services specifically used for Node.js.

## Project Status

Shared-Common is a personal project, now in experimental mode. In most cases, you should choose a different library.

## Install

```
$ npm install @manishbasnetnp/shared-common
```

## Usage

```js
const { successResponse, failureResponse } = require('@manishbasnetnp/shared-common')
const response = {
    data: 'example'
};
// In case of success
successResponse(200, 'success', response);

// In case of failure 
failureResponse(500, 'Something went wrong.');
```

_Thank you._

## License

Shared-Common is freely distributable under the terms of the [MIT license][license-url].

[license-image]: https://img.shields.io/badge/license-MIT-blue.svg?style=flat
[license-url]: LICENSE
[npm-url]: https://npmjs.org/package/@manishbasnetnp/shared-common
