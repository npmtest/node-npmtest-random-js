# npmtest-random-js

#### test coverage for  [random-js (v1.0.8)](https://github.com/ckknight/random-js)  [![npm package](https://img.shields.io/npm/v/npmtest-random-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-random-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-random-js.svg)](https://travis-ci.org/npmtest/node-npmtest-random-js)

#### A mathematically correct random number generator library for JavaScript.

[![NPM](https://nodei.co/npm/random-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/random-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-random-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-random-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-random-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-random-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-random-js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-random-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-random-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-random-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-random-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-random-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-random-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-random-js/build/test-report.html](https://npmtest.github.io/node-npmtest-random-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-random-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-random-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-random-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-random-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-random-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-random-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-random-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-random-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Cameron Kenneth Knight"
    },
    "bugs": {
        "url": "https://github.com/ckknight/random-js/issues"
    },
    "dependencies": {},
    "description": "A mathematically correct random number generator library for JavaScript.",
    "devDependencies": {
        "karma": "~0.10.9",
        "karma-chrome-launcher": "~0.1.2",
        "karma-coffee-preprocessor": "~0.1.2",
        "karma-coverage": "~0.1.5",
        "karma-firefox-launcher": "~0.1.3",
        "karma-html2js-preprocessor": "~0.1.0",
        "karma-jasmine": "~0.1.5",
        "karma-phantomjs-launcher": "~0.1.1",
        "karma-requirejs": "~0.2.1",
        "karma-script-launcher": "~0.1.0",
        "requirejs": "~2.1.10"
    },
    "directories": {},
    "dist": {
        "shasum": "968fd689a6f25d6c0aac766283de2f688c9c190a",
        "tarball": "https://registry.npmjs.org/random-js/-/random-js-1.0.8.tgz"
    },
    "gitHead": "8a51f321c1fb1725a593fec59299af6ad7118631",
    "homepage": "https://github.com/ckknight/random-js",
    "keywords": [
        "random"
    ],
    "license": "MIT",
    "main": "lib/random",
    "maintainers": [
        {
            "name": "ckknight"
        }
    ],
    "name": "random-js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/ckknight/random-js.git"
    },
    "scripts": {
        "test": "jasmine-node lib/random.js spec/",
        "uglify": "uglifyjs lib/random.js -o lib/random.min.js -m -c"
    },
    "testling": {
        "files": "spec/*.js"
    },
    "version": "1.0.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
