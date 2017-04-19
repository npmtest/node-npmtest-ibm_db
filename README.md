# npmtest-ibm_db

#### test coverage for  [ibm_db (v2.0.0)](https://github.com/ibmdb/node-ibm_db/)  [![npm package](https://img.shields.io/npm/v/npmtest-ibm_db.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ibm_db) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ibm_db.svg)](https://travis-ci.org/npmtest/node-npmtest-ibm_db)

#### IBM DB2 and IBM Informix bindings for node

[![NPM](https://nodei.co/npm/ibm_db.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ibm_db)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ibm_db/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ibm_db/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ibm_db/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ibm_db/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ibm_db/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ibm_db/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ibm_db/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ibm_db/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ibm_db/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ibm_db/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ibm_db/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ibm_db/build/test-report.html](https://npmtest.github.io/node-npmtest-ibm_db/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ibm_db/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ibm_db/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ibm_db/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ibm_db/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ibm_db/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ibm_db/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ibm_db/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ibm_db/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "IBM"
    },
    "bugs": {
        "url": "https://github.com/ibmdb/node-ibm_db/issues"
    },
    "contributors": [
        {
            "name": "IBM"
        }
    ],
    "dependencies": {
        "bindings": "~1.2.1",
        "fstream": "~1.0.10",
        "nan": "~2.3.5",
        "q": "^1.4.1",
        "request": "^2.75.0",
        "targz": "^1.0.1",
        "unzipper": "~0.7.2"
    },
    "description": "IBM DB2 and IBM Informix bindings for node",
    "devDependencies": {
        "async": "^2.0.1",
        "bluebird": "^3.4.3",
        "moment": "^2.14.1"
    },
    "directories": {
        "example": "examples",
        "test": "test"
    },
    "dist": {
        "shasum": "8eb1e14112c2e823b0155f2bec443e466fc369e2",
        "tarball": "https://registry.npmjs.org/ibm_db/-/ibm_db-2.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "homepage": "https://github.com/ibmdb/node-ibm_db/",
    "keywords": [
        "node",
        "odbc",
        "db2",
        "driver"
    ],
    "license": "MIT",
    "main": "lib/odbc.js",
    "maintainers": [
        {
            "name": "ibmdb"
        }
    ],
    "name": "ibm_db",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/ibmdb/node-ibm_db.git"
    },
    "scripts": {
        "install": "node installer/driverInstall.js",
        "test": "cd test && node run-tests.js"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
