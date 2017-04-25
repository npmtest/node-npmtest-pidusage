# npmtest-pidusage

#### basic test coverage for  [pidusage (v1.1.1)](https://github.com/soyuka/pidusage)  [![npm package](https://img.shields.io/npm/v/npmtest-pidusage.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pidusage) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pidusage.svg)](https://travis-ci.org/npmtest/node-npmtest-pidusage)

#### Cross-platform process cpu % and memory usage of a PID — Edit

[![NPM](https://nodei.co/npm/pidusage.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pidusage)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pidusage/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pidusage/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pidusage/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pidusage/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pidusage/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-pidusage/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-pidusage/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pidusage/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pidusage/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pidusage/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pidusage/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pidusage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pidusage/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pidusage/build/test-report.html](https://npmtest.github.io/node-npmtest-pidusage/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pidusage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pidusage/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pidusage/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pidusage/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pidusage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pidusage/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pidusage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pidusage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "soyuka"
    },
    "bugs": {
        "url": "https://github.com/soyuka/pidusage/issues"
    },
    "dependencies": {},
    "description": "Cross-platform process cpu % and memory usage of a PID — Edit",
    "devDependencies": {
        "chai": "~3.4.1",
        "mocha": "~2.3.4",
        "mockery": "1.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5a46184da84549cc03c8380e0aeb68248fd214b3",
        "tarball": "https://registry.npmjs.org/pidusage/-/pidusage-1.1.1.tgz"
    },
    "gitHead": "77801358dd8f3cf476b8ded0777dccc24c256c93",
    "homepage": "https://github.com/soyuka/pidusage",
    "keywords": [
        "pid",
        "usage",
        "ps",
        "cpu",
        "memory",
        "proc"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "soyuka"
        }
    ],
    "name": "pidusage",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/soyuka/pidusage.git"
    },
    "scripts": {
        "test": "mocha test/test.js --reporter min && node test/stresstest.js"
    },
    "version": "1.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
