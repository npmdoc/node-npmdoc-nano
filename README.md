# npmdoc-nano

#### api documentation for  [nano (v6.2.0)](http://github.com/dscape/nano)  [![npm package](https://img.shields.io/npm/v/npmdoc-nano.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nano) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nano.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nano)

#### The official CouchDB client for Node.js

[![NPM](https://nodei.co/npm/nano.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nano)

- [https://npmdoc.github.io/node-npmdoc-nano/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nano/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nano/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nano/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nano/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nano/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Apache CouchDB",
        "url": "http://couchdb.apache.org"
    },
    "bugs": {
        "url": "https://github.com/dscape/nano/issues"
    },
    "dependencies": {
        "debug": "^2.0.0",
        "errs": "^0.3.0",
        "follow": "^0.12.1",
        "request": "^2.53.0",
        "underscore": "^1.7.0"
    },
    "description": "The official CouchDB client for Node.js",
    "devDependencies": {
        "async": "^0.9.0",
        "endswith": "^0.0.0",
        "istanbul": "^0.3.2",
        "jscs": "^1.7.0",
        "jshint": "^2.5.6",
        "nock": "^0.48.1",
        "tape": "^3.0.0",
        "tape-it": "^0.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "314aa08f41e7da388bd2132b9f97ecbc67e057a0",
        "tarball": "https://registry.npmjs.org/nano/-/nano-6.2.0.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "c03b5528b6b0759f7e001b722199f824163ad3a0",
    "homepage": "http://github.com/dscape/nano",
    "keywords": [
        "couchdb",
        "data",
        "request",
        "json",
        "nosql",
        "micro",
        "nano",
        "database"
    ],
    "license": "Apache-2.0",
    "main": "./lib/nano.js",
    "maintainers": [
        {
            "name": "dscape"
        },
        {
            "name": "jhs"
        },
        {
            "name": "jo"
        },
        {
            "name": "pgte"
        }
    ],
    "name": "nano",
    "optionalDependencies": {},
    "pre-commit": [
        "jshint",
        "codestyle",
        "mocked",
        "test",
        "checkcoverage"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/dscape/nano.git"
    },
    "scripts": {
        "checkcoverage": "istanbul check-coverage --statements 100 --functions 100 --lines 100 --branches 100",
        "codestyle": "jscs -p google tests/*/*/*.js lib/*.js",
        "coverage": "open coverage/lcov-report/index.html",
        "jshint": "jshint tests/*/*/*.js lib/*.js",
        "mocked": "tape tests/*/*/*.js",
        "test": "DEBUG=* NOCK_OFF=true istanbul cover tape tests/*/*/*.js",
        "unmocked": "NOCK_OFF=true tape tests/*/*/*.js"
    },
    "version": "6.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
