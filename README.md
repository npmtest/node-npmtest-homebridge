# npmtest-homebridge

#### basic test coverage for  homebridge (v0.4.19)  [![npm package](https://img.shields.io/npm/v/npmtest-homebridge.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-homebridge) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-homebridge.svg)](https://travis-ci.org/npmtest/node-npmtest-homebridge)

#### HomeKit support for the impatient

[![NPM](https://nodei.co/npm/homebridge.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/homebridge)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-homebridge/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-homebridge/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-homebridge/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-homebridge/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-homebridge/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-homebridge/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-homebridge/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-homebridge/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-homebridge/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-homebridge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-homebridge/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-homebridge/build/test-report.html](https://npmtest.github.io/node-npmtest-homebridge/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-homebridge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-homebridge/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-homebridge/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-homebridge/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-homebridge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-homebridge/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-homebridge/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-homebridge/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "homebridge",
    "description": "HomeKit support for the impatient",
    "version": "0.4.19",
    "scripts": {
        "dev": "DEBUG=* ./bin/homebridge -D -P example-plugins/ || true"
    },
    "author": {
        "name": "Nick Farina"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/nfarina/homebridge.git"
    },
    "bugs": {
        "url": "http://github.com/nfarina/homebridge/issues"
    },
    "license": "ISC",
    "bin": {
        "homebridge": "bin/homebridge"
    },
    "engines": {
        "node": ">=4.3.2"
    },
    "preferGlobal": true,
    "dependencies": {
        "chalk": "^1.1.1",
        "commander": "2.8.1",
        "hap-nodejs": "0.4.24",
        "semver": "5.0.3",
        "node-persist": "^0.0.8"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
