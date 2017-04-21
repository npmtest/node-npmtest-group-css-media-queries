# npmtest-group-css-media-queries

#### basic test coverage for  [group-css-media-queries (v1.4.1)](https://github.com/Se7enSky/group-css-media-queries#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-group-css-media-queries.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-group-css-media-queries) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-group-css-media-queries.svg)](https://travis-ci.org/npmtest/node-npmtest-group-css-media-queries)

#### CSS postprocessing: group media queries. Useful for postprocessing preprocessed CSS files :)

[![NPM](https://nodei.co/npm/group-css-media-queries.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/group-css-media-queries)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-group-css-media-queries/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-group-css-media-queries/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-group-css-media-queries/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-group-css-media-queries/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-group-css-media-queries/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-group-css-media-queries/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-group-css-media-queries/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-group-css-media-queries/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-group-css-media-queries/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-group-css-media-queries/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-group-css-media-queries/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-group-css-media-queries/build/test-report.html](https://npmtest.github.io/node-npmtest-group-css-media-queries/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-group-css-media-queries/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-group-css-media-queries/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-group-css-media-queries/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-group-css-media-queries/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-group-css-media-queries/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-group-css-media-queries/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-group-css-media-queries/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-group-css-media-queries/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ivan Kravchenko"
    },
    "bin": {
        "group-css-media-queries": "./bin/group-css-media-queries"
    },
    "bugs": {
        "url": "https://github.com/Se7enSky/group-css-media-queries/issues"
    },
    "dependencies": {
        "css-parse": "^2.0.0",
        "css-stringify": "^2.0.0"
    },
    "description": "CSS postprocessing: group media queries. Useful for postprocessing preprocessed CSS files :)",
    "devDependencies": {
        "chai": "^1.10.0",
        "coffee-script": "*",
        "mocha": "^2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "8e54cb31cc45a9c5e08eb838940b8a28038d7175",
        "tarball": "https://registry.npmjs.org/group-css-media-queries/-/group-css-media-queries-1.4.1.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "ccc4601287ba83441965168794d3f749bf45fd12",
    "homepage": "https://github.com/Se7enSky/group-css-media-queries#readme",
    "keywords": [
        "css",
        "group",
        "media",
        "queries",
        "postprocessing",
        "postprocessor"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "krava"
        }
    ],
    "name": "group-css-media-queries",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Se7enSky/group-css-media-queries.git"
    },
    "scripts": {
        "prepublish": "coffee -c index.coffee",
        "test": "mocha --compilers coffee:coffee-script/register"
    },
    "version": "1.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
