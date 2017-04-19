# npmtest-bigrig

#### basic test coverage for  [bigrig (v1.3.0)](https://github.com/GoogleChrome/node-big-rig#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-bigrig.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bigrig) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bigrig.svg)](https://travis-ci.org/npmtest/node-npmtest-bigrig)

#### A CLI and node module for parsing trace (timeline) files from Chrome.

[![NPM](https://nodei.co/npm/bigrig.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bigrig)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bigrig/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bigrig/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bigrig/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bigrig/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bigrig/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bigrig/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bigrig/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bigrig/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bigrig/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bigrig/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bigrig/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bigrig/build/test-report.html](https://npmtest.github.io/node-npmtest-bigrig/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bigrig/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bigrig/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bigrig/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bigrig/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bigrig/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bigrig/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bigrig/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bigrig/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Paul Lewis",
        "url": "Google"
    },
    "bin": {
        "bigrig": "bigrig.js"
    },
    "bugs": {
        "url": "https://github.com/GoogleChrome/node-big-rig/issues"
    },
    "dependencies": {
        "cli-color": "^1.1.0",
        "mkdirp": "^0.5.1",
        "yargs": "^3.29.0"
    },
    "description": "A CLI and node module for parsing trace (timeline) files from Chrome.",
    "devDependencies": {
        "babel-eslint": "^4.1.3",
        "chai": "^3.4.0",
        "eslint": "^1.8.0",
        "mocha": "^2.3.3"
    },
    "directories": {},
    "dist": {
        "shasum": "1f2a4822082c514659d06d7873ff4386b0d179e5",
        "tarball": "https://registry.npmjs.org/bigrig/-/bigrig-1.3.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "2c74a0411fb2fc97bbb689bdc847959c0548a639",
    "homepage": "https://github.com/GoogleChrome/node-big-rig#readme",
    "keywords": [
        "chrome",
        "trace",
        "cli"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "aerotwist"
        }
    ],
    "name": "bigrig",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/GoogleChrome/node-big-rig.git"
    },
    "scripts": {
        "test": "eslint . && mocha test/*.js --timeout 60000"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
