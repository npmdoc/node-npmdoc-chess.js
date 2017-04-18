# npmdoc-chess.js

#### api documentation for  [chess.js (v0.10.2)](https://github.com/jhlywa/chess.js)  [![npm package](https://img.shields.io/npm/v/npmdoc-chess.js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-chess.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-chess.js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-chess.js)

#### A Javascript chess library for chess move generation/validation, piece placement/movement, and check/checkmate/draw detection

[![NPM](https://nodei.co/npm/chess.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/chess.js)

- [https://npmdoc.github.io/node-npmdoc-chess.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-chess.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-chess.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-chess.js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-chess.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-chess.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeff Hlywa",
        "url": "https://github.com/jhlywa"
    },
    "bugs": {
        "url": "https://github.com/jhlywa/chess.js/issues"
    },
    "dependencies": {},
    "description": "A Javascript chess library for chess move generation/validation, piece placement/movement, and check/checkmate/draw detection",
    "devDependencies": {
        "chai": "2.3.0",
        "mocha": "2.2.4",
        "uglify-js": "2.4.21"
    },
    "directories": {},
    "dist": {
        "shasum": "eacefa2067155f87f046e80cc12d2019eef1b81a",
        "tarball": "https://registry.npmjs.org/chess.js/-/chess.js-0.10.2.tgz"
    },
    "filename": "chess.min.js",
    "gitHead": "c81a2889921d88e523e5dd54b85d643b63f40415",
    "homepage": "https://github.com/jhlywa/chess.js",
    "keywords": [
        "chess"
    ],
    "license": "BSD-2-Clause",
    "main": "chess.js",
    "maintainers": [
        {
            "name": "jhlywa"
        }
    ],
    "name": "chess.js",
    "npmFileMap": [
        {
            "basePath": "",
            "files": [
                "chess*.js"
            ]
        }
    ],
    "npmName": "chess.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jhlywa/chess.js.git"
    },
    "scripts": {
        "minify": "uglifyjs chess.js -c -m --comments 'license' > chess.min.js",
        "test": "mocha"
    },
    "version": "0.10.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
