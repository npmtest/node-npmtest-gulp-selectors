# npmtest-gulp-selectors

#### test coverage for  [gulp-selectors (v0.1.9)](https://github.com/calebthebrewer/gulp-selectors)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-selectors.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-selectors) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-selectors.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-selectors)

#### Minify CSS selectors.

[![NPM](https://nodei.co/npm/gulp-selectors.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-selectors)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-selectors/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-selectors/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-selectors/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-selectors/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-selectors/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-selectors/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-selectors/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-selectors/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-selectors/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-selectors/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-selectors/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-selectors/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-selectors/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-selectors/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-selectors/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-selectors/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-selectors/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-selectors/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-selectors/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-selectors/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-selectors/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Caleb Brewer"
    },
    "bugs": {
        "url": "https://github.com/calebthebrewer/gulp-selectors/issues"
    },
    "dependencies": {
        "event-stream": "~3.1.7",
        "gulp-util": "~3.0.1",
        "lodash": "~2.4.1",
        "multimatch": "^1.0.1"
    },
    "description": "Minify CSS selectors.",
    "devDependencies": {
        "codeclimate-test-reporter": "0.0.4",
        "gulp": "~3.8.11",
        "istanbul": "^0.3.2",
        "jscoverage": "~0.5.6",
        "vows": "~0.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "427a2e55794f4f24bef92f30e882294285559ec2",
        "tarball": "https://registry.npmjs.org/gulp-selectors/-/gulp-selectors-0.1.9.tgz"
    },
    "gitHead": "db67b02c541ba5bf1fa274d3314de6ca3ac4eaec",
    "homepage": "https://github.com/calebthebrewer/gulp-selectors",
    "keywords": [
        "gulp",
        "gulpplugin",
        "munch",
        "minify",
        "css",
        "selectors",
        "styles",
        "compress"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "calebthebrewer"
        }
    ],
    "name": "gulp-selectors",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/calebthebrewer/gulp-selectors.git"
    },
    "scripts": {
        "codeclimate": "cat ./coverage/lcov.info | codeclimate",
        "coverage": "istanbul cover ./node_modules/vows/bin/vows --spec",
        "test": "vows --spec",
        "test-report": "npm run coverage && npm run codeclimate"
    },
    "version": "0.1.9"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
