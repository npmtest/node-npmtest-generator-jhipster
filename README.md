# npmtest-generator-jhipster

#### basic test coverage for  [generator-jhipster (v4.3.0)](http://jhipster.github.io/)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-jhipster.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-jhipster) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-jhipster.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-jhipster)

#### Spring Boot + Angular in one handy generator

[![NPM](https://nodei.co/npm/generator-jhipster.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-jhipster)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-jhipster/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-jhipster/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-jhipster/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-jhipster/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-jhipster/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-jhipster/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-jhipster/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-jhipster/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-jhipster/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-jhipster/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-jhipster/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-jhipster/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-jhipster/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-jhipster/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-jhipster/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-jhipster/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-jhipster/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-jhipster/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-jhipster/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-jhipster/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-jhipster/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Julien Dubois",
        "url": "https://github.com/jdubois"
    },
    "bugs": {
        "url": "https://github.com/jhipster/generator-jhipster/issues"
    },
    "dependencies": {
        "chalk": "1.1.3",
        "cheerio": "0.22.0",
        "ejs": "2.5.6",
        "glob": "7.1.1",
        "html-wiring": "1.2.0",
        "insight": "0.8.4",
        "jhipster-core": "1.2.9",
        "js-yaml": "3.8.3",
        "lodash": "4.17.4",
        "mkdirp": "0.5.1",
        "pluralize": "4.0.0",
        "randexp": "0.4.5",
        "semver": "5.3.0",
        "shelljs": "0.7.7",
        "yeoman-generator": "1.1.1",
        "yo": "1.8.5"
    },
    "description": "Spring Boot + Angular in one handy generator",
    "devDependencies": {
        "eslint": "3.19.0",
        "eslint-config-airbnb-base": "11.1.3",
        "eslint-plugin-import": "2.2.0",
        "fs-extra": "2.1.2",
        "mocha": "3.2.0",
        "yeoman-assert": "3.0.0",
        "yeoman-test": "1.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2538007c235446ed73f1a729d25ae2619398ce1b",
        "tarball": "https://registry.npmjs.org/generator-jhipster/-/generator-jhipster-4.3.0.tgz"
    },
    "engines": {
        "node": ">=6.9.0",
        "npm": ">=2.14.2"
    },
    "files": [
        "generators"
    ],
    "gitHead": "05995ed037dbe3bbd7ae1d1b033cb3b45c4c994c",
    "homepage": "http://jhipster.github.io/",
    "keywords": [
        "yeoman-generator",
        "Java",
        "Spring",
        "Spring Boot",
        "Spring Security",
        "JPA",
        "Hibernate",
        "AngularJS",
        "Angular",
        "Twitter Bootstrap"
    ],
    "license": "Apache-2.0",
    "main": "app/index.js",
    "maintainers": [
        {
            "name": "deepu105"
        },
        {
            "name": "jdubois"
        },
        {
            "name": "mathieuaa"
        }
    ],
    "name": "generator-jhipster",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jhipster/generator-jhipster.git"
    },
    "scripts": {
        "lint": "eslint .",
        "lint-fix": "eslint . --fix",
        "pretest": "eslint .",
        "test": "mocha --timeout 20000 --slow 0 --reporter spec"
    },
    "version": "4.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
