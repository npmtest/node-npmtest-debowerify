# npmtest-debowerify

#### basic test coverage for  [debowerify (v1.5.0)](https://github.com/eugeneware/debowerify#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-debowerify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-debowerify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-debowerify.svg)](https://travis-ci.org/npmtest/node-npmtest-debowerify)

#### A browserify transform to enable the easy use of bower components in browserify client javascript projects. This can be used in conjunction with deamdify to require AMD components from bower as well.

[![NPM](https://nodei.co/npm/debowerify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/debowerify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-debowerify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-debowerify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-debowerify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-debowerify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-debowerify/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-debowerify/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-debowerify/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-debowerify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-debowerify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-debowerify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-debowerify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-debowerify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-debowerify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-debowerify/build/test-report.html](https://npmtest.github.io/node-npmtest-debowerify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-debowerify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-debowerify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-debowerify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-debowerify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-debowerify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-debowerify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-debowerify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-debowerify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eugene Ware"
    },
    "bugs": {
        "url": "https://github.com/eugeneware/debowerify/issues"
    },
    "dependencies": {
        "bower": "~1.3.12",
        "esprima": "^2.0.0",
        "ordered-ast-traverse": "^1.1.1",
        "through": "~2.3.4"
    },
    "description": "A browserify transform to enable the easy use of bower components in browserify client javascript projects. This can be used in conjunction with deamdify to require AMD components from bower as well.",
    "devDependencies": {
        "browserify": "~9.0.0",
        "chai": "~1.9.0",
        "deamdify": "~0.1.1",
        "domready": "~1.0.4",
        "mocha": "^2.1.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "0813bd5b8fee8f5fb77ebafd62e2979a17dcdaff",
        "tarball": "https://registry.npmjs.org/debowerify/-/debowerify-1.5.0.tgz"
    },
    "gitHead": "7eeabf2f69778a70a1c29cb7772589227c9cc41a",
    "homepage": "https://github.com/eugeneware/debowerify#readme",
    "keywords": [
        "bower",
        "component",
        "components",
        "browserify",
        "transform"
    ],
    "license": "BSD",
    "main": "index.js",
    "maintainers": [
        {
            "name": "nharbour"
        },
        {
            "name": "eugeneware"
        }
    ],
    "name": "debowerify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/eugeneware/debowerify.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "1.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
