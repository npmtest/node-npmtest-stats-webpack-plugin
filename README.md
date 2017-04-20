# npmtest-stats-webpack-plugin

#### basic test coverage for  stats-webpack-plugin (v0.6.0)  [![npm package](https://img.shields.io/npm/v/npmtest-stats-webpack-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-stats-webpack-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-stats-webpack-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-stats-webpack-plugin)

#### Write the stats of a build to a file.

[![NPM](https://nodei.co/npm/stats-webpack-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/stats-webpack-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-stats-webpack-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-stats-webpack-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-stats-webpack-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-stats-webpack-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-stats-webpack-plugin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-stats-webpack-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-stats-webpack-plugin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-stats-webpack-plugin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-stats-webpack-plugin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-stats-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-stats-webpack-plugin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-stats-webpack-plugin/build/test-report.html](https://npmtest.github.io/node-npmtest-stats-webpack-plugin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-stats-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-stats-webpack-plugin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-stats-webpack-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-stats-webpack-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stats-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stats-webpack-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-stats-webpack-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-stats-webpack-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "stats-webpack-plugin",
    "description": "Write the stats of a build to a file.",
    "version": "0.6.0",
    "license": "MIT",
    "author": {
        "name": "Daniel Perez Alvarez",
        "url": "http://unindented.org/"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/unindented/stats-webpack-plugin.git"
    },
    "keywords": [
        "stats",
        "webpack"
    ],
    "scripts": {
        "spec": "mocha",
        "lint": "eslint .",
        "test": "npm run lint && npm run spec"
    },
    "peerDependencies": {
        "webpack": "^1.0||^2.1.0-beta||^2.2.0-rc"
    },
    "devDependencies": {
        "chai": "^3.5.0",
        "eslint": "^3.13.1",
        "eslint-config-standard": "^6.2.1",
        "eslint-plugin-promise": "^3.4.0",
        "eslint-plugin-standard": "^2.0.1",
        "mocha": "^3.2.0",
        "node-libs-browser": "^2.0.0",
        "rimraf": "^2.5.4",
        "webpack": "^1.14.0"
    },
    "dependencies": {
        "lodash": "^4.17.4"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
