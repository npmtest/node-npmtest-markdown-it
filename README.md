# npmtest-markdown-it

#### basic test coverage for  [markdown-it (v8.3.1)](https://github.com/markdown-it/markdown-it#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-markdown-it.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-markdown-it) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-markdown-it.svg)](https://travis-ci.org/npmtest/node-npmtest-markdown-it)

#### Markdown-it - modern pluggable markdown parser.

[![NPM](https://nodei.co/npm/markdown-it.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/markdown-it)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-markdown-it/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-markdown-it/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-markdown-it/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-markdown-it/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-markdown-it/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-markdown-it/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-markdown-it/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-markdown-it/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-markdown-it/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-markdown-it/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-markdown-it/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-markdown-it/build/test-report.html](https://npmtest.github.io/node-npmtest-markdown-it/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-markdown-it/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-markdown-it/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-markdown-it/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-markdown-it/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-markdown-it/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-markdown-it/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-markdown-it/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-markdown-it/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "markdown-it": "bin/markdown-it.js"
    },
    "bugs": {
        "url": "https://github.com/markdown-it/markdown-it/issues"
    },
    "dependencies": {
        "argparse": "^1.0.7",
        "entities": "~1.1.1",
        "linkify-it": "^2.0.0",
        "mdurl": "^1.0.1",
        "uc.micro": "^1.0.3"
    },
    "description": "Markdown-it - modern pluggable markdown parser.",
    "devDependencies": {
        "ansi": "^0.3.0",
        "autoprefixer-stylus": "^0.11.0",
        "benchmark": "~2.1.0",
        "browserify": "*",
        "chai": "^3.4.1",
        "coveralls": "~2.11.9",
        "eslint": "^3.5.0",
        "express": "^4.14.0",
        "highlight.js": "^9.2.0",
        "istanbul": "^0.4.5",
        "jade": "~1.11.0",
        "markdown-it-abbr": "^1.0.4",
        "markdown-it-container": "^2.0.0",
        "markdown-it-deflist": "^2.0.0",
        "markdown-it-emoji": "^1.1.1",
        "markdown-it-footnote": "^3.0.1",
        "markdown-it-for-inline": "~0.1.0",
        "markdown-it-ins": "^2.0.0",
        "markdown-it-mark": "^2.0.0",
        "markdown-it-sub": "^1.0.0",
        "markdown-it-sup": "^1.0.0",
        "markdown-it-testgen": "~0.1.3",
        "mocha": "*",
        "ndoc": "^5.0.0",
        "stylus": "~0.54.2",
        "uglify-js": "^2.7.3"
    },
    "directories": {},
    "dist": {
        "shasum": "2f4b622948ccdc193d66f3ca2d43125ac4ac7323",
        "tarball": "https://registry.npmjs.org/markdown-it/-/markdown-it-8.3.1.tgz"
    },
    "files": [
        "index.js",
        "bin/",
        "lib/",
        "dist/"
    ],
    "gitHead": "427cc20c9b9dd73b8e00b33f48cc643042261a1b",
    "homepage": "https://github.com/markdown-it/markdown-it#readme",
    "keywords": [
        "markdown",
        "parser",
        "commonmark",
        "markdown-it",
        "markdown-it-plugin"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "vitaly"
        }
    ],
    "name": "markdown-it",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/markdown-it/markdown-it.git"
    },
    "scripts": {
        "heroku-postbuild": "npm install express",
        "test": "make test"
    },
    "version": "8.3.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
