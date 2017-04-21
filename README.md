# npmtest-rollup-plugin-buble

#### basic test coverage for  [rollup-plugin-buble (v0.15.0)](https://gitlab.com/rich-harris/rollup-plugin-buble#README)  [![npm package](https://img.shields.io/npm/v/npmtest-rollup-plugin-buble.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rollup-plugin-buble) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rollup-plugin-buble.svg)](https://travis-ci.org/npmtest/node-npmtest-rollup-plugin-buble)

#### Compile ES2015 with buble

[![NPM](https://nodei.co/npm/rollup-plugin-buble.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rollup-plugin-buble)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rollup-plugin-buble/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rollup-plugin-buble/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rollup-plugin-buble/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rollup-plugin-buble/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rollup-plugin-buble/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rollup-plugin-buble/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rollup-plugin-buble/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rollup-plugin-buble/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rollup-plugin-buble/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rollup-plugin-buble/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rollup-plugin-buble/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rollup-plugin-buble/build/test-report.html](https://npmtest.github.io/node-npmtest-rollup-plugin-buble/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rollup-plugin-buble/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rollup-plugin-buble/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rollup-plugin-buble/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rollup-plugin-buble/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rollup-plugin-buble/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rollup-plugin-buble/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rollup-plugin-buble/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rollup-plugin-buble/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rich Harris"
    },
    "bugs": {
        "url": "https://gitlab.com/rich-harris/rollup-plugin-buble/issues"
    },
    "dependencies": {
        "buble": "^0.15.0",
        "rollup-pluginutils": "^1.5.0"
    },
    "description": "Compile ES2015 with buble",
    "devDependencies": {
        "eslint": "^3.3.1",
        "mocha": "^3.0.2",
        "rollup": "^0.37.0"
    },
    "directories": {},
    "dist": {
        "shasum": "83c3e89c7fd2266c7918f41ba3980313519c7fd0",
        "tarball": "https://registry.npmjs.org/rollup-plugin-buble/-/rollup-plugin-buble-0.15.0.tgz"
    },
    "files": [
        "dist",
        "README.md"
    ],
    "gitHead": "d37080b8885c0f047c33492505fee6d7ace147cb",
    "homepage": "https://gitlab.com/rich-harris/rollup-plugin-buble#README",
    "jsnext:main": "dist/rollup-plugin-buble.es.js",
    "license": "MIT",
    "main": "dist/rollup-plugin-buble.cjs.js",
    "maintainers": [
        {
            "name": "rich_harris"
        }
    ],
    "name": "rollup-plugin-buble",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://gitlab.com/rich-harris/rollup-plugin-buble.git"
    },
    "scripts": {
        "build": "npm run build:cjs && npm run build:es",
        "build:cjs": "rollup -c -f cjs -o dist/rollup-plugin-buble.cjs.js",
        "build:es": "rollup -c -f es6 -o dist/rollup-plugin-buble.es.js",
        "lint": "eslint src",
        "prepublish": "npm run lint && rm -rf dist && npm test && npm run build:es",
        "pretest": "npm run build:cjs",
        "test": "mocha test/test.js"
    },
    "version": "0.15.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
