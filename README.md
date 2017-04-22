# npmtest-editorconfig-tools

#### basic test coverage for  editorconfig-tools (v0.1.1)  [![npm package](https://img.shields.io/npm/v/npmtest-editorconfig-tools.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-editorconfig-tools) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-editorconfig-tools.svg)](https://travis-ci.org/npmtest/node-npmtest-editorconfig-tools)

#### Tools for verifying/fixing code style based on an EditorConfig file

[![NPM](https://nodei.co/npm/editorconfig-tools.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/editorconfig-tools)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-editorconfig-tools/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-editorconfig-tools/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-editorconfig-tools/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-editorconfig-tools/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-editorconfig-tools/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-editorconfig-tools/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-editorconfig-tools/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-editorconfig-tools/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-editorconfig-tools/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-editorconfig-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-editorconfig-tools/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-editorconfig-tools/build/test-report.html](https://npmtest.github.io/node-npmtest-editorconfig-tools/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-editorconfig-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-editorconfig-tools/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-editorconfig-tools/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-editorconfig-tools/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-editorconfig-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-editorconfig-tools/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-editorconfig-tools/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-editorconfig-tools/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "editorconfig-tools",
    "description": "Tools for verifying/fixing code style based on an EditorConfig file",
    "version": "0.1.1",
    "author": "Sean Lang <slang800@gmail.com>",
    "bin": {
        "editorconfig-tools": "bin/index.js"
    },
    "bugs": {
        "url": "https://github.com/slang800/editorconfig-tools/issues"
    },
    "dependencies": {
        "argparse": "^0.1.15",
        "detect-indent": "^0.1.4",
        "editorconfig": "^0.12.1",
        "fobject": "0.0.3",
        "graceful-fs": "^3.0.4",
        "lodash": "^2.4.1",
        "require-tree": "^0.3.3",
        "when": "^3.1.0"
    },
    "devDependencies": {
        "coffee-script": "^1.7.1",
        "mocha": "^2.0.1",
        "should": "^4.1.0"
    },
    "keywords": [
        "editorconfig",
        "tools",
        "validate",
        "fix",
        "enforce",
        "code-quality",
        "formatting",
        "infer"
    ],
    "license": "MIT",
    "main": "lib",
    "repository": {
        "type": "git",
        "url": "git://github.com/slang800/editorconfig-tools.git"
    },
    "scripts": {
        "test": "mocha"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
