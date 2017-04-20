# npmtest-parker

#### basic test coverage for  [parker (v0.0.10)](https://github.com/katiefenn/parker)  [![npm package](https://img.shields.io/npm/v/npmtest-parker.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-parker) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-parker.svg)](https://travis-ci.org/npmtest/node-npmtest-parker)

#### Stylesheet analysis tool for CSS

[![NPM](https://nodei.co/npm/parker.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/parker)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-parker/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-parker/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-parker/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-parker/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-parker/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-parker/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-parker/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-parker/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-parker/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-parker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-parker/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-parker/build/test-report.html](https://npmtest.github.io/node-npmtest-parker/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-parker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-parker/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-parker/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-parker/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-parker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-parker/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-parker/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-parker/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "parker",
    "description": "Stylesheet analysis tool for CSS",
    "keywords": [
        "css",
        "stylesheet",
        "analysis"
    ],
    "version": "0.0.10",
    "main": "parker.js",
    "dependencies": {
        "async": "~0.2.10",
        "cli-color": "*",
        "graceful-fs": "~3.0.2",
        "lodash": "^3.2.0",
        "minimist": "0.0.7"
    },
    "devDependencies": {
        "chai": "*",
        "mocha": "*",
        "sinon": "*",
        "sinon-chai": "*"
    },
    "scripts": {
        "test": "mocha --no-colors --reporter spec"
    },
    "bin": {
        "parker": "./parker.js"
    },
    "homepage": "https://github.com/katiefenn/parker",
    "bugs": "https://github.com/katiefenn/parker/issues",
    "author": "Katie Fenn",
    "repository": "https://github.com/katiefenn/parker",
    "preferGlobal": true,
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
