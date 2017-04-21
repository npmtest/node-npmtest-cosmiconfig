# npmtest-cosmiconfig

#### basic test coverage for  [cosmiconfig (v2.1.1)](https://github.com/davidtheclark/cosmiconfig#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cosmiconfig.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cosmiconfig) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cosmiconfig.svg)](https://travis-ci.org/npmtest/node-npmtest-cosmiconfig)

#### Find and load configuration from a package.json property, rc file, or CommonJS module

[![NPM](https://nodei.co/npm/cosmiconfig.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cosmiconfig)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cosmiconfig/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cosmiconfig/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cosmiconfig/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cosmiconfig/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cosmiconfig/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cosmiconfig/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cosmiconfig/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cosmiconfig/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cosmiconfig/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cosmiconfig/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cosmiconfig/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cosmiconfig/build/test-report.html](https://npmtest.github.io/node-npmtest-cosmiconfig/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cosmiconfig/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cosmiconfig/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cosmiconfig/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cosmiconfig/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cosmiconfig/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cosmiconfig/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cosmiconfig/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cosmiconfig/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "cosmiconfig",
    "version": "2.1.1",
    "description": "Find and load configuration from a package.json property, rc file, or CommonJS module",
    "main": "index.js",
    "files": [
        "index.js",
        "lib"
    ],
    "scripts": {
        "lint": "node-version-gte-4 && eslint . || echo \"ESLint not supported\"",
        "ava": "ava test/*.test.js",
        "coverage": "nyc npm run ava && nyc report --reporter=html && open coverage/index.html",
        "test": "npm run ava && npm run lint"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/davidtheclark/cosmiconfig.git"
    },
    "keywords": [
        "load",
        "configuration",
        "config"
    ],
    "author": "David Clark <david.dave.clark@gmail.com>",
    "contributors": [
        "Bogdan Chadkin <trysound@yandex.ru>"
    ],
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/davidtheclark/cosmiconfig/issues"
    },
    "homepage": "https://github.com/davidtheclark/cosmiconfig#readme",
    "dependencies": {
        "js-yaml": "^3.4.3",
        "minimist": "^1.2.0",
        "object-assign": "^4.1.0",
        "os-homedir": "^1.0.1",
        "parse-json": "^2.2.0",
        "require-from-string": "^1.1.0"
    },
    "devDependencies": {
        "ava": "0.16.0",
        "eslint": "3.5.0",
        "eslint-config-davidtheclark-node": "^0.2.0",
        "eslint-plugin-node": "^2.0.0",
        "expect": "^1.20.2",
        "lodash": "4.16.1",
        "node-version-check": "^2.1.1",
        "nyc": "^8.3.0",
        "sinon": "1.17.6"
    },
    "engines": {
        "node": ">=0.12"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
