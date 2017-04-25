# npmtest-node-mac

#### basic test coverage for  node-mac (v0.1.8)  [![npm package](https://img.shields.io/npm/v/npmtest-node-mac.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-mac) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-mac.svg)](https://travis-ci.org/npmtest/node-npmtest-node-mac)

#### Support daemon creation and management on Mac.

[![NPM](https://nodei.co/npm/node-mac.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-mac)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-mac/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-mac/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-mac/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-mac/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-mac/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-node-mac/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-node-mac/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-mac/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-mac/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-mac/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-mac/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-mac/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-mac/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-mac/build/test-report.html](https://npmtest.github.io/node-npmtest-node-mac/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-mac/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-mac/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-mac/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-mac/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-mac/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-mac/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-mac/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-mac/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-mac",
    "version": "0.1.8",
    "description": "Support daemon creation and management on Mac.",
    "keywords": [
        "ngn",
        "mac",
        "daemon",
        "service"
    ],
    "author": "Corey Butler <corey@coreybutler.com>",
    "devDependencies": {
        "mocha": "*"
    },
    "main": "lib/node-mac.js",
    "os": [
        "darwin"
    ],
    "dependencies": {
        "optimist": "~0.6.0",
        "plist": "~0.4.3"
    },
    "readmeFilename": "README.md",
    "scripts": {
        "test": "mocha"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/coreybutler/node-mac.git"
    },
    "license": "MIT",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
