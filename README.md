# npmtest-gulp-atomicscss

#### basic test coverage for  [gulp-atomicscss (v0.4.0)](https://github.com/internetErik/gulp-atomicscss)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-atomicscss.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-atomicscss) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-atomicscss.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-atomicscss)

#### A plugin for Gulp that takes text, scans for class attributes and generates an scss file from the classes

[![NPM](https://nodei.co/npm/gulp-atomicscss.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-atomicscss)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-atomicscss/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-atomicscss/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-atomicscss/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-atomicscss/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-atomicscss/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-atomicscss/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-atomicscss/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-atomicscss/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-atomicscss/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-atomicscss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-atomicscss/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-atomicscss/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-atomicscss/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-atomicscss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-atomicscss/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-atomicscss/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-atomicscss/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-atomicscss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-atomicscss/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-atomicscss/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-atomicscss/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-atomicscss",
    "version": "0.4.0",
    "description": "A plugin for Gulp that takes text, scans for class attributes and generates an scss file from the classes",
    "keywords": [
        "gulpplugin",
        "scss"
    ],
    "homepage": "https://github.com/internetErik/gulp-atomicscss",
    "bugs": "https://github.com/internetErik/gulp-atomicscss/issues",
    "author": {
        "name": "Erik Christianson",
        "url": "https://github.com/internetErik"
    },
    "main": "./index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/internetErik/gulp-atomicscss.git"
    },
    "dependencies": {
        "through2": "*",
        "gulp-util": "~2.2.0",
        "lodash": ">=2.4.1"
    },
    "devDependencies": {
        "mocha": "*",
        "coveralls": "*",
        "mocha-lcov-reporter": "*",
        "istanbul": "*",
        "event-stream": "*",
        "should": "~2.1.0"
    },
    "engines": {
        "node": ">=0.8.0",
        "npm": ">=1.2.10"
    },
    "licenses": [
        {
            "type": "MIT"
        }
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
