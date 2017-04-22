# npmtest-slm

#### basic test coverage for  [slm (v1.0.0)](https://github.com/slm-lang/slm)  [![npm package](https://img.shields.io/npm/v/npmtest-slm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-slm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-slm.svg)](https://travis-ci.org/npmtest/node-npmtest-slm)

#### Slim/Jade like templating engine

[![NPM](https://nodei.co/npm/slm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/slm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-slm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-slm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-slm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-slm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-slm/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-slm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-slm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-slm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-slm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-slm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-slm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-slm/build/test-report.html](https://npmtest.github.io/node-npmtest-slm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-slm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-slm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-slm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-slm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-slm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-slm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-slm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-slm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Yury Korolev"
    },
    "browser": "lib/slm_browser.js",
    "bugs": {
        "url": "https://github.com/slm-lang/slm/issues"
    },
    "dependencies": {},
    "description": "Slim/Jade like templating engine",
    "devDependencies": {
        "codeclimate-test-reporter": "^0.4.0",
        "gulp": "^3.8.11",
        "gulp-concat": "^2.5.2",
        "gulp-gzip": "^1.0.0",
        "gulp-load-plugins": "^1.2.2",
        "gulp-replace": "^0.5.3",
        "gulp-size": "^2.1.0",
        "gulp-uglify": "^2.0.0",
        "gulp-util": "^3.0.4",
        "gulp-webpack": "^1.3.0",
        "jest": "^18.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "67e46e652178eb8f029ff1b12c81e6c8bf757907",
        "tarball": "https://registry.npmjs.org/slm/-/slm-1.0.0.tgz"
    },
    "gitHead": "c7505a0c4cfdcee8ac1c261e7228412b75169276",
    "homepage": "https://github.com/slm-lang/slm",
    "jest": {
        "testEnvironment": "node",
        "testPathIgnorePatterns": [
            "__tests__/helper.js$"
        ],
        "coverageThreshold": {
            "global": {
                "branches": 95.5,
                "functions": 97,
                "lines": 97,
                "statements": 97
            }
        }
    },
    "keywords": [
        "html",
        "jade",
        "pug",
        "slim",
        "template"
    ],
    "license": "ISC",
    "main": "lib/slm.js",
    "maintainers": [
        {
            "name": "yury"
        }
    ],
    "name": "slm",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/slm-lang/slm.git"
    },
    "scripts": {
        "test": "jest"
    },
    "version": "1.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
