# npmtest-jake

#### test coverage for  [jake (v8.0.15)](https://github.com/jakejs/jake#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-jake.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jake) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jake.svg)](https://travis-ci.org/npmtest/node-npmtest-jake)

#### JavaScript build tool, similar to Make or Rake

[![NPM](https://nodei.co/npm/jake.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jake)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jake/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jake/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jake/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jake/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jake/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jake/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jake/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jake/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jake/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jake/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jake/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jake/build/test-report.html](https://npmtest.github.io/node-npmtest-jake/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jake/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jake/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jake/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jake/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jake/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jake/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jake/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jake/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matthew Eernisse",
        "url": "http://fleegix.org"
    },
    "bin": {
        "jake": "./bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/jakejs/jake/issues"
    },
    "dependencies": {
        "async": "0.9.x",
        "chalk": "0.4.x",
        "filelist": "0.0.x",
        "minimatch": "3.x",
        "utilities": "1.0.x"
    },
    "description": "JavaScript build tool, similar to Make or Rake",
    "devDependencies": {
        "q": "0.9.x"
    },
    "directories": {},
    "dist": {
        "shasum": "f0da7d58e790ac1a8f86e6ee0f193e5d9230eabb",
        "tarball": "https://registry.npmjs.org/jake/-/jake-8.0.15.tgz"
    },
    "engines": {
        "node": "*"
    },
    "homepage": "https://github.com/jakejs/jake#readme",
    "keywords": [
        "build",
        "cli",
        "make",
        "rake"
    ],
    "license": "Apache-2.0",
    "main": "./lib/jake.js",
    "maintainers": [
        {
            "name": "benng"
        },
        {
            "name": "danfinlay"
        },
        {
            "name": "mde"
        },
        {
            "name": "ondrej"
        }
    ],
    "name": "jake",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/jakejs/jake.git"
    },
    "scripts": {
        "test": "./bin/cli.js test"
    },
    "version": "8.0.15"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
