## content-types-by-file-extension

  Yields the corresponding MIME content types for file extensions.
  Goal is a simple and independent implementation for a simple task.

## Usage

```js
//import the module
const contentTypesByFileExtension = require('content-types-by-file-extension')

//This yields the ContentType for ".html" files: "text/html"
const htmlContentType = contentTypesByFileExtension[html]
```

## Installation

This is a [Node.js](https://nodejs.org/en/) module available through the
[npm registry](https://www.npmjs.com/).

Before installing, [download and install Node.js](https://nodejs.org/en/download/).

Installation is done using the
[`npm install` command](https://docs.npmjs.com/getting-started/installing-npm-packages-locally):

```bash
$ npm
```

## License

  [MIT](LICENSE)
