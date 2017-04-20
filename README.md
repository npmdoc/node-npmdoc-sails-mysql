# npmdoc-sails-mysql

#### api documentation for  sails-mysql (v0.11.5)  [![npm package](https://img.shields.io/npm/v/npmdoc-sails-mysql.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sails-mysql) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sails-mysql.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sails-mysql)

#### MySQL adapter for Sails.js

[![NPM](https://nodei.co/npm/sails-mysql.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sails-mysql)

- [https://npmdoc.github.io/node-npmdoc-sails-mysql/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sails-mysql/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails-mysql/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails-mysql/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sails-mysql/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sails-mysql/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sails-mysql",
    "version": "0.11.5",
    "description": "MySQL adapter for Sails.js",
    "main": "lib/adapter.js",
    "scripts": {
        "test": "make test",
        "docker": "docker-compose run adapter bash"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/balderdashy/sails-mysql.git"
    },
    "keywords": [
        "mysql",
        "orm",
        "waterline",
        "sails"
    ],
    "author": "Mike McNeil",
    "license": "MIT",
    "readmeFilename": "README.md",
    "dependencies": {
        "async": "1.5.2",
        "lodash": "3.10.1",
        "mysql": "2.10.2",
        "waterline-cursor": "0.0.6",
        "waterline-errors": "0.10.1",
        "waterline-sequel": "0.5.7"
    },
    "devDependencies": {
        "captains-log": "~0.11.11",
        "mocha": "2.4.1",
        "should": "8.2.0",
        "waterline-adapter-tests": "~0.11.1"
    },
    "waterlineAdapter": {
        "waterlineVersion": "~0.10.0",
        "interfaces": [
            "semantic",
            "queryable",
            "migratable",
            "associations",
            "sql"
        ],
        "features": [
            "crossAdapter",
            "unique",
            "autoIncrement.sequential"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
