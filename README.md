# npmdoc-wunderline

#### basic api documentation for  [wunderline (v4.5.0)](http://wayneashleyberry.github.io/wunderline/)  [![npm package](https://img.shields.io/npm/v/npmdoc-wunderline.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-wunderline) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-wunderline.svg)](https://travis-ci.org/npmdoc/node-npmdoc-wunderline)

#### Wunderlist for your command line!

[![NPM](https://nodei.co/npm/wunderline.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wunderline)

- [https://npmdoc.github.io/node-npmdoc-wunderline/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wunderline/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wunderline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wunderline/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-wunderline/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-wunderline/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Wayne Ashley Berry",
        "url": "https://twitter.com/waynethebrain"
    },
    "bin": {
        "wunderline": "./wunderline.js"
    },
    "bugs": {
        "url": "https://github.com/wayneashleyberry/wunderline/issues"
    },
    "dependencies": {
        "async": "^1.0.0",
        "chalk": "^1.0.0",
        "columnify": "^1.5.1",
        "commander": "^2.8.1",
        "configstore": "^1.2.0",
        "fuzzysearch": "^1.0.3",
        "get-stdin": "^5.0.0",
        "inquirer": "~1.0.3",
        "lodash.find": "^4.4.0",
        "lodash.trunc": "^3.0.3",
        "moment": "^2.11.2",
        "opn": "^4.0.0",
        "request": "^2.55.0",
        "vorpal": "^1.11.2",
        "wordwrap": "^1.0.0"
    },
    "description": "Wunderlist for your command line!",
    "devDependencies": {
        "bin-check": "^3.0.0",
        "codeclimate-test-reporter": "^0.3.1",
        "istanbul": "^0.4.2",
        "standard": "^7.0.0",
        "tape": "^4.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "72f852846ca0d45d0e2864e9da6703657f3000a6",
        "tarball": "https://registry.npmjs.org/wunderline/-/wunderline-4.5.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "961c69fe8e0aeb7e5a3b3f3e199bc1d6fcef4591",
    "homepage": "http://wayneashleyberry.github.io/wunderline/",
    "keywords": [
        "wunderlist",
        "wunderline",
        "task",
        "todo",
        "productivity"
    ],
    "license": "MIT",
    "main": "wunderline.js",
    "maintainers": [
        {
            "name": "laurenwaller"
        },
        {
            "name": "michaelthorne"
        },
        {
            "name": "next"
        },
        {
            "name": "thor77"
        },
        {
            "name": "wayneashleyberry"
        }
    ],
    "name": "wunderline",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/wayneashleyberry/wunderline.git"
    },
    "scripts": {
        "cover": "istanbul cover test.js",
        "report": "codeclimate-test-reporter < ./coverage/lcov.info",
        "test": "standard && tape test.js"
    },
    "version": "4.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
