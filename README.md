# npmtest-xregexp

#### basic test coverage for  [xregexp (v3.2.0)](http://xregexp.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-xregexp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-xregexp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-xregexp.svg)](https://travis-ci.org/npmtest/node-npmtest-xregexp)

#### Extended regular expressions

[![NPM](https://nodei.co/npm/xregexp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/xregexp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-xregexp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-xregexp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-xregexp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-xregexp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-xregexp/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-xregexp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-xregexp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-xregexp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-xregexp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-xregexp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-xregexp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-xregexp/build/test-report.html](https://npmtest.github.io/node-npmtest-xregexp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-xregexp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-xregexp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-xregexp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-xregexp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xregexp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xregexp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-xregexp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-xregexp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Steven Levithan"
    },
    "bugs": {
        "url": "https://github.com/slevithan/xregexp/issues"
    },
    "dependencies": {},
    "description": "Extended regular expressions",
    "devDependencies": {
        "browserify": "^12.0.1",
        "jasmine": "^2.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "cb3601987bfe2695b584000c18f1c4a8c322878e",
        "tarball": "https://registry.npmjs.org/xregexp/-/xregexp-3.2.0.tgz"
    },
    "files": [
        "src",
        "xregexp-all.js",
        "LICENSE"
    ],
    "gitHead": "ddf24c536821faf2493625ed6bdc3cb5ce2c6fdd",
    "homepage": "http://xregexp.com/",
    "keywords": [
        "regex",
        "regexp",
        "regular expression",
        "unicode"
    ],
    "license": "MIT",
    "main": "xregexp-all.js",
    "maintainers": [
        {
            "name": "slevithan"
        }
    ],
    "name": "xregexp",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/slevithan/xregexp.git"
    },
    "scripts": {
        "build": "browserify src/index.js --standalone XRegExp > xregexp-all.js",
        "pretest": "npm run build",
        "test": "jasmine JASMINE_CONFIG_PATH=tests/jasmine.json"
    },
    "version": "3.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
