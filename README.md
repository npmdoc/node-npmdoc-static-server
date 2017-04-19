# npmdoc-static-server

#### api documentation for  [static-server (v2.0.4)](https://github.com/nbluis/static-server#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-static-server.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-static-server) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-static-server.svg)](https://travis-ci.org/npmdoc/node-npmdoc-static-server)

#### A simple http server to serve static resource files from a local directory.

[![NPM](https://nodei.co/npm/static-server.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/static-server)

- [https://npmdoc.github.io/node-npmdoc-static-server/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-static-server/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-static-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-static-server/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-static-server/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-static-server/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eduardo Bohrer"
    },
    "bin": {
        "static-server": "./bin/static-server.js"
    },
    "bugs": {
        "url": "https://github.com/nbluis/static-server/issues"
    },
    "dependencies": {
        "chalk": "^0.5.1",
        "commander": "^2.3.0",
        "file-size": "0.0.5",
        "mime": "^1.2.11"
    },
    "description": "A simple http server to serve static resource files from a local directory.",
    "devDependencies": {
        "istanbul": "^0.3.0",
        "mocha": "^1.21.4",
        "should": "^4.0.4",
        "supertest": "^0.15.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f6cd4946f09fc95f264fec4fa1ff442ca176dfc3",
        "tarball": "https://registry.npmjs.org/static-server/-/static-server-2.0.4.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "0e80faa065b4696b6dc9ccb3307407cebd980d04",
    "homepage": "https://github.com/nbluis/static-server#readme",
    "keywords": [
        "static",
        "server",
        "local",
        "assets"
    ],
    "license": {
        "type": "MIT",
        "url": "http://creativecommons.org/licenses/MIT/"
    },
    "main": "./server.js",
    "maintainers": [
        {
            "name": "nbluis"
        }
    ],
    "name": "static-server",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/nbluis/static-server.git"
    },
    "scripts": {
        "start": "node server.js",
        "test": "mocha",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly"
    },
    "version": "2.0.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
