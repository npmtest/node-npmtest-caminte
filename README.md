# npmtest-caminte

#### basic test coverage for  [caminte (v0.3.6)](http://camintejs.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-caminte.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-caminte) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-caminte.svg)](https://travis-ci.org/npmtest/node-npmtest-caminte)

#### ORM for every database: redis, mysql, neo4j, mongodb, rethinkdb, postgres, sqlite, tingodb

[![NPM](https://nodei.co/npm/caminte.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/caminte)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-caminte/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-caminte/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-caminte/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-caminte/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-caminte/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-caminte/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-caminte/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-caminte/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-caminte/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-caminte/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-caminte/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-caminte/build/test-report.html](https://npmtest.github.io/node-npmtest-caminte/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-caminte/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-caminte/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-caminte/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-caminte/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-caminte/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-caminte/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-caminte/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-caminte/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Aleksej Gordejev",
        "url": "http://www.gordejev.lv"
    },
    "bugs": {
        "url": "https://github.com/biggora/caminte/issues"
    },
    "contributors": [
        {
            "name": "Aleksej Gordejev"
        },
        {
            "name": "Anatoliy Chakkaev"
        },
        {
            "name": "Julien Guimont"
        },
        {
            "name": "Joseph Junker"
        },
        {
            "name": "Henri Bergius"
        },
        {
            "name": "redvulps"
        },
        {
            "name": "Felipe Sateler"
        },
        {
            "name": "Amir M. Mahmoudi"
        },
        {
            "name": "Justinas Stankevičius"
        },
        {
            "name": "Rick O'Toole"
        },
        {
            "name": "Nicholas Westlake"
        },
        {
            "name": "Michael Pauley"
        },
        {
            "name": "Tyrone Dougherty"
        }
    ],
    "dependencies": {
        "bluebird": "^3.4.6",
        "uuid": "^3.0.1"
    },
    "description": "ORM for every database: redis, mysql, neo4j, mongodb, rethinkdb, postgres, sqlite, tingodb",
    "devDependencies": {
        "arangojs": "4.2.0 - 4.4.0",
        "async": "latest",
        "cassandra-driver": ">=2.1.0",
        "coffee-script": "*",
        "cradle": ">= 0.6.0",
        "felix-couchdb": ">= 1.0.0",
        "generic-pool": "latest",
        "istanbul": "latest",
        "jshint": "2.x",
        "mocha": "latest",
        "moment": "latest",
        "mongodb": ">= 2.0.0",
        "mongoose": ">= 3.0.0",
        "mysql": ">= 2.0.0",
        "node-neo4j": "^2.0.3",
        "pg": ">= 4.0.0",
        "redis": ">= 0.12.0",
        "rethinkdb": ">= 1.16",
        "riak-js": ">= 1.0.0",
        "semicov": "latest",
        "should": "latest",
        "sqlite3": "^3.1.1",
        "underscore": "latest"
    },
    "directories": {
        "lib": "lib",
        "media": "media",
        "support": "support",
        "test": "test"
    },
    "dist": {
        "shasum": "4eb77cfd3a3a596c1b92c6fb0276fb52d9d8b334",
        "tarball": "https://registry.npmjs.org/caminte/-/caminte-0.3.6.tgz"
    },
    "engines": {
        "node": ">=0.10",
        "npm": ">=1.0"
    },
    "gitHead": "eed8e8bef566f979d5776c1a19eda13820c0eade",
    "homepage": "http://camintejs.com/",
    "keywords": [
        "orm",
        "cross-db",
        "caminte",
        "database",
        "adapter",
        "redis",
        "mysql",
        "mariadb",
        "mongodb",
        "neo4j",
        "nano",
        "couchdb",
        "firebird",
        "postgres",
        "sqlite3",
        "tingodb",
        "rethinkdb",
        "arangodb",
        "promise"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "biggora"
        }
    ],
    "name": "caminte",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/biggora/caminte.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "0.3.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
