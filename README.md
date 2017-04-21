# npmdoc-indico.io

#### api documentation for  [indico.io (v0.10.5)](https://github.com/IndicoDataSolutions/IndicoIo-node)  [![npm package](https://img.shields.io/npm/v/npmdoc-indico.io.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-indico.io) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-indico.io.svg)](https://travis-ci.org/npmdoc/node-npmdoc-indico.io)

#### A Node.js wrapper for the Indico’s API

[![NPM](https://nodei.co/npm/indico.io.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/indico.io)

- [https://npmdoc.github.io/node-npmdoc-indico.io/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-indico.io/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-indico.io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-indico.io/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-indico.io/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-indico.io/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "indico.io",
    "description": "A Node.js wrapper for the Indico’s API",
    "version": "0.10.5",
    "homepage": "https://github.com/IndicoDataSolutions/IndicoIo-node",
    "author": {
        "name": "Joseph Núñez <toctochello@gmail.com>"
    },
    "contributors": [
        "Madison May <madison@indico.io>",
        "Chris Lee <chris@indico.io>",
        "Aidan McLaughlin <aidan@indico.io"
    ],
    "keywords": [],
    "repository": {
        "type": "git",
        "url": "git://github.com/IndicoDataSolutions/IndicoIo-node.git"
    },
    "bugs": {
        "url": "https://github.com/IndicoDataSolutions/IndicoIo-node/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/IndicoDataSolutions/IndicoIo-node/blob/master/LICENSE"
        }
    ],
    "main": "./lib/indico",
    "dependencies": {
        "bluebird": "^2.9.24",
        "config-ini": "^0.2.2",
        "expand-tilde": "^1.2.0",
        "file-type": "^2.11.0",
        "request": "^2.36.0",
        "valid-url": "^1.0.9"
    },
    "optionalDependencies": {
        "lwip": "^0.0.9"
    },
    "devDependencies": {
        "should": "~3.0.1",
        "mocha": "~1.17.0",
        "chai": "1.9.1"
    },
    "scripts": {
        "test": "mocha test/*.js test/integration/*.js"
    },
    "js-flags": "--harmony"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
