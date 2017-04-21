# npmtest-jsverify

#### basic test coverage for  [jsverify (v0.8.2)](http://jsverify.github.io/)  [![npm package](https://img.shields.io/npm/v/npmtest-jsverify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jsverify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jsverify.svg)](https://travis-ci.org/npmtest/node-npmtest-jsverify)

#### Property-based testing for JavaScript.

[![NPM](https://nodei.co/npm/jsverify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsverify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jsverify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsverify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jsverify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jsverify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jsverify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jsverify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jsverify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jsverify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jsverify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsverify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jsverify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jsverify/build/test-report.html](https://npmtest.github.io/node-npmtest-jsverify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jsverify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jsverify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jsverify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsverify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsverify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsverify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jsverify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jsverify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jsverify",
    "description": "Property-based testing for JavaScript.",
    "version": "0.8.2",
    "homepage": "http://jsverify.github.io/",
    "author": {
        "name": "Oleg Grenrus",
        "url": "http://oleg.fi"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/jsverify/jsverify.git"
    },
    "bugs": {
        "url": "https://github.com/jsverify/jsverify/issues"
    },
    "license": "MIT",
    "main": "lib/jsverify.js",
    "types": "lib/jsverify.d.ts",
    "engines": {
        "node": ">= 0.8.0"
    },
    "scripts": {
        "test": "make test"
    },
    "devDependencies": {
        "@types/mocha": "^2.2.40",
        "bluebird": "^3.1.1",
        "browserify": "^14.0.0",
        "chai": "^3.0.0",
        "david": "^11.0.0",
        "eslint": "^3.3.1",
        "esprima": "^3.0.0",
        "istanbul": "^0.4.1",
        "jasmine-core": "^2.4.1",
        "jscs": "^3.0.7",
        "jshint": "^2.7.0",
        "karma": "^1.2.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-cli": "^1.0.1",
        "karma-firefox-launcher": "^1.0.0",
        "karma-jasmine": "^1.0.2",
        "karma-mocha": "^1.1.1",
        "ljs": "~0.3.0",
        "lodash": "^4.4.0",
        "mocha": "^3.0.2",
        "npm-freeze": "^0.1.3",
        "q": "~2.0.2",
        "ts-node": "^3.0.0",
        "tslint": "^5.0.0",
        "typescript": "^2.2.1",
        "underscore": "^1.8.2",
        "when": "~3.7.2"
    },
    "keywords": [
        "testing",
        "unit testing",
        "TDD",
        "property-based testing",
        "quickcheck",
        "quick check",
        "jscheck"
    ],
    "dependencies": {
        "lazy-seq": "^1.0.0",
        "rc4": "~0.1.5",
        "trampa": "^1.0.0",
        "typify-parser": "^1.1.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
