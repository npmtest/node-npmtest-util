# npmtest-util

#### basic test coverage for  [util (v0.10.3)](https://github.com/defunctzombie/node-util)  [![npm package](https://img.shields.io/npm/v/npmtest-util.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-util) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-util.svg)](https://travis-ci.org/npmtest/node-npmtest-util)

#### Node.JS util module

[![NPM](https://nodei.co/npm/util.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/util)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-util/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-util/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-util/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-util/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-util/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-util/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-util/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-util/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-util/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-util/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-util/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-util/build/test-report.html](https://npmtest.github.io/node-npmtest-util/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-util/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-util/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-util/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-util/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-util/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-util/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-util/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-util/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Joyent",
        "url": "http://www.joyent.com"
    },
    "browser": {
        "./support/isBuffer.js": "./support/isBufferBrowser.js"
    },
    "bugs": {
        "url": "https://github.com/defunctzombie/node-util/issues"
    },
    "dependencies": {
        "inherits": "2.0.1"
    },
    "description": "Node.JS util module",
    "devDependencies": {
        "zuul": "~1.0.9"
    },
    "directories": {},
    "dist": {
        "shasum": "7afb1afe50805246489e3db7fe0ed379336ac0f9",
        "tarball": "https://registry.npmjs.org/util/-/util-0.10.3.tgz"
    },
    "homepage": "https://github.com/defunctzombie/node-util",
    "keywords": [
        "util"
    ],
    "license": "MIT",
    "main": "./util.js",
    "maintainers": [
        {
            "name": "shtylman"
        }
    ],
    "name": "util",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/defunctzombie/node-util.git"
    },
    "scripts": {
        "test": "node test/node/*.js && zuul test/browser/*.js"
    },
    "version": "0.10.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
