# npmtest-npmd

#### basic test coverage for  [npmd (v1.4.0)](https://github.com/dominictarr/npmd)  [![npm package](https://img.shields.io/npm/v/npmtest-npmd.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npmd) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npmd.svg)](https://travis-ci.org/npmtest/node-npmtest-npmd)

#### distributed npm client

[![NPM](https://nodei.co/npm/npmd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npmd)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npmd/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npmd/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npmd/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npmd/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npmd/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npmd/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npmd/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npmd/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npmd/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npmd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npmd/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npmd/build/test-report.html](https://npmtest.github.io/node-npmtest-npmd/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npmd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npmd/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npmd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npmd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npmd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npmd/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npmd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npmd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dominic Tarr",
        "url": "http://dominictarr.com"
    },
    "bin": {
        "npmd": "./index.js"
    },
    "bugs": {
        "url": "https://github.com/dominictarr/npmd/issues"
    },
    "dependencies": {
        "add-deps": "~1.2.0",
        "get-deps": "~2.0.4",
        "levelup": "~0.18.2",
        "medeadown": "~1.0.6",
        "mkdirp": "~0.5.0",
        "npmd-bin": "1.2",
        "npmd-build": "~0.1.3",
        "npmd-cache": "~4.3.1",
        "npmd-config": "~1.2.2",
        "npmd-install": "~5.1.2",
        "npmd-resolve": "~7.8.0",
        "npmd-tree": "~3.3.4",
        "to-camel-case": "~0.2.0"
    },
    "description": "distributed npm client",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "fc98f9ecbc8814c2651183436b0a4b3da0d3e3aa",
        "tarball": "https://registry.npmjs.org/npmd/-/npmd-1.4.0.tgz"
    },
    "gitHead": "88d73e1072e4632bc4f472a641bc16106e63561e",
    "homepage": "https://github.com/dominictarr/npmd",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dominictarr"
        }
    ],
    "name": "npmd",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dominictarr/npmd.git"
    },
    "scripts": {
        "build": "browserify client.js > static/bundle.js",
        "test": "./test.sh"
    },
    "version": "1.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
