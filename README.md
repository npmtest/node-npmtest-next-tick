# npmtest-next-tick

#### test coverage for  [next-tick (v1.0.0)](https://github.com/medikoo/next-tick#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-next-tick.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-next-tick) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-next-tick.svg)](https://travis-ci.org/npmtest/node-npmtest-next-tick)

#### Environment agnostic nextTick polyfill

[![NPM](https://nodei.co/npm/next-tick.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/next-tick)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-next-tick/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-next-tick/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-next-tick/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-next-tick/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-next-tick/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-next-tick/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-next-tick/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-next-tick/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-next-tick/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-next-tick/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-next-tick/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-next-tick/build/test-report.html](https://npmtest.github.io/node-npmtest-next-tick/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-next-tick/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-next-tick/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-next-tick/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-next-tick/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-next-tick/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-next-tick/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-next-tick/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-next-tick/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mariusz Nowak",
        "url": "http://www.medikoo.com/"
    },
    "bugs": {
        "url": "https://github.com/medikoo/next-tick/issues"
    },
    "dependencies": {},
    "description": "Environment agnostic nextTick polyfill",
    "devDependencies": {
        "tad": "^0.2.4",
        "xlint": "^0.2.2",
        "xlint-jslint-medikoo": "^0.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "ca86d1fe8828169b0120208e3dc8424b9db8342c",
        "tarball": "https://registry.npmjs.org/next-tick/-/next-tick-1.0.0.tgz"
    },
    "gitHead": "5b1c1d0ad81f3c494ca74db1cb8012c0f6a7e512",
    "homepage": "https://github.com/medikoo/next-tick#readme",
    "keywords": [
        "nexttick",
        "setImmediate",
        "setTimeout",
        "async"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "medikoo"
        }
    ],
    "name": "next-tick",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/medikoo/next-tick.git"
    },
    "scripts": {
        "lint": "node node_modules/xlint/bin/xlint --linter=node_modules/xlint-jslint-medikoo/index.js --no-cache --no-stream",
        "lint-console": "node node_modules/xlint/bin/xlint --linter=node_modules/xlint-jslint-medikoo/index.js --watch",
        "test": "node node_modules/tad/bin/tad"
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
