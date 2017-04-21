# npmtest-lessify

#### basic test coverage for  lessify (v1.0.1)  [![npm package](https://img.shields.io/npm/v/npmtest-lessify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lessify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lessify.svg)](https://travis-ci.org/npmtest/node-npmtest-lessify)

#### Middleware and Browserify transform for less files

[![NPM](https://nodei.co/npm/lessify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lessify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lessify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lessify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lessify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lessify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lessify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lessify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lessify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lessify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lessify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lessify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lessify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lessify/build/test-report.html](https://npmtest.github.io/node-npmtest-lessify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lessify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lessify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lessify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lessify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lessify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lessify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lessify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lessify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "lessify",
    "version": "1.0.1",
    "description": "Middleware and Browserify transform for less files",
    "main": "./index.js",
    "browserify": "./transform.js",
    "scripts": {
        "test": "node test/lessify.js"
    },
    "author": "Drew Stokes",
    "license": "BSD-2-Clause",
    "dependencies": {
        "cssify": "^0.6.0",
        "less": "^2.2.0",
        "through": "^2.3.6"
    },
    "devDependencies": {
        "tape": "~2.1.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/dstokes/lessify.git"
    },
    "keywords": [
        "browserify",
        "less",
        "transform"
    ],
    "bugs": {
        "url": "https://github.com/dstokes/lessify/issues"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
