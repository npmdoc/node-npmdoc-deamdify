# npmdoc-deamdify

#### basic api documentation for  [deamdify (v0.3.0)](https://github.com/jaredhanson/deamdify#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-deamdify.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-deamdify) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-deamdify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-deamdify)

#### Browserify transform that converts AMD to CommonJS.

[![NPM](https://nodei.co/npm/deamdify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/deamdify)

- [https://npmdoc.github.io/node-npmdoc-deamdify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-deamdify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-deamdify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-deamdify/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-deamdify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-deamdify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jared Hanson",
        "url": "http://www.jaredhanson.net/"
    },
    "bugs": {
        "url": "http://github.com/jaredhanson/deamdify/issues"
    },
    "dependencies": {
        "escodegen": "^1.8.1",
        "esprima": "^2.1.0",
        "estraverse": "^4.2.0",
        "through": "^2.3.8"
    },
    "description": "Browserify transform that converts AMD to CommonJS.",
    "devDependencies": {
        "chai": "^3.5.0",
        "mocha": "^3.2.0",
        "test-peer-range": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "b91eb0b92ee7d6d0780546998db767234a8a2ac1",
        "tarball": "https://registry.npmjs.org/deamdify/-/deamdify-0.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.6.0"
    },
    "gitHead": "fbb3c7c95c8fdd771d2fbcb57508d34f14b155bc",
    "homepage": "https://github.com/jaredhanson/deamdify#readme",
    "keywords": [
        "browserify",
        "transform",
        "requirejs",
        "amd"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://www.opensource.org/licenses/MIT"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "jaredhanson"
        },
        {
            "name": "tbranyen"
        }
    ],
    "name": "deamdify",
    "optionalDependencies": {},
    "peerDependencies": {
        "browserify": ">= 2.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/jaredhanson/deamdify.git"
    },
    "scripts": {
        "test": "test-peer-range browserify",
        "test-main": "mocha --reporter spec --require test/bootstrap/node test/*.test.js"
    },
    "version": "0.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
