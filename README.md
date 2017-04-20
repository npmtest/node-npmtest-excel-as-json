# npmtest-excel-as-json

#### basic test coverage for  [excel-as-json (v2.0.0)](https://github.com/stevetarver/excel-as-json)  [![npm package](https://img.shields.io/npm/v/npmtest-excel-as-json.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-excel-as-json) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-excel-as-json.svg)](https://travis-ci.org/npmtest/node-npmtest-excel-as-json)

#### Convert Excel data to JSON

[![NPM](https://nodei.co/npm/excel-as-json.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/excel-as-json)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-excel-as-json/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-excel-as-json/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-excel-as-json/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-excel-as-json/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-excel-as-json/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-excel-as-json/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-excel-as-json/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-excel-as-json/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-excel-as-json/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-excel-as-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-excel-as-json/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-excel-as-json/build/test-report.html](https://npmtest.github.io/node-npmtest-excel-as-json/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-excel-as-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-excel-as-json/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-excel-as-json/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-excel-as-json/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-excel-as-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-excel-as-json/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-excel-as-json/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-excel-as-json/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "excel-as-json",
    "version": "2.0.0",
    "description": "Convert Excel data to JSON",
    "author": "Steve Tarver <steve.tarver@gmail.com>",
    "license": "MIT",
    "main": "lib/excel-as-json.js",
    "scripts": {
        "clean": "tools/clean.sh",
        "build": "tools/build.sh",
        "test": "tools/test.sh",
        "dist": "tools/dist.sh",
        "codecov": "cat ./coverage/lcov.info | ./node_modules/.bin/codecov",
        "coveralls": "cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js",
        "prepublish": "tools/dist.sh"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/stevetarver/excel-as-json.git"
    },
    "keywords": [
        "Excel",
        "JSON",
        "convert"
    ],
    "bugs": {
        "url": "https://github.com/stevetarver/excel-as-json/issues"
    },
    "homepage": "https://github.com/stevetarver/excel-as-json",
    "dependencies": {
        "excel": "0.1.7"
    },
    "devDependencies": {
        "chai": "3.5.0",
        "codecov.io": "0.1.6",
        "coffee-coverage": "1.0.1",
        "coffee-script": "1.10.0",
        "coveralls": "2.11.9",
        "istanbul": "0.4.3",
        "mocha": "2.5.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
