# npmtest-colors.css

#### basic test coverage for  [colors.css (v3.0.0)](http://clrs.cc)  [![npm package](https://img.shields.io/npm/v/npmtest-colors.css.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-colors.css) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-colors.css.svg)](https://travis-ci.org/npmtest/node-npmtest-colors.css)

#### Better default colors for the web. A collection of skin classes for faster prototyping and nicer looking sites.

[![NPM](https://nodei.co/npm/colors.css.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/colors.css)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-colors.css/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-colors.css/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-colors.css/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-colors.css/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-colors.css/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-colors.css/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-colors.css/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-colors.css/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-colors.css/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-colors.css/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-colors.css/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-colors.css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-colors.css/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-colors.css/build/test-report.html](https://npmtest.github.io/node-npmtest-colors.css/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-colors.css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-colors.css/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-colors.css/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-colors.css/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-colors.css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-colors.css/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-colors.css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-colors.css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "@mrmrs",
        "url": "http://mrmrs.cc"
    },
    "bugs": {
        "url": "http://github.com/mrmrs/colors/issues"
    },
    "contributors": [
        {
            "name": "@mrmrs"
        },
        {
            "name": "@ilanbiala"
        },
        {
            "name": "@kdrdgn",
            "url": "http://www.twitter.com/kdrdgn"
        },
        {
            "name": "@tenmilestereo",
            "url": "http://www.lewiscowper.com"
        },
        {
            "name": "@nschonni",
            "url": "http://wet-boew.github.io/"
        },
        {
            "name": "SiR-DanieL"
        },
        {
            "name": "@enyo",
            "url": "http://colorglare.com"
        }
    ],
    "dependencies": {},
    "description": "Better default colors for the web. A collection of skin classes for faster prototyping and nicer looking sites.",
    "devDependencies": {
        "tachyons-cli": "^0.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "511cf42fb8a7199a8cbef49c88a4ea4f1d8f9efc",
        "tarball": "https://registry.npmjs.org/colors.css/-/colors.css-3.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10.22"
    },
    "gitHead": "d7aeca45e958696ab17456a1512dc368b5b41fea",
    "homepage": "http://clrs.cc",
    "keywords": [
        "colors",
        "design",
        "a11y",
        "postcss",
        "palette",
        "css",
        "oocss"
    ],
    "license": "MIT",
    "main": "js/colors.js",
    "maintainers": [
        {
            "name": "mrmrs"
        }
    ],
    "name": "colors.css",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/mrmrs/colors.git"
    },
    "scripts": {
        "start": "tachyons src/colors.css > css/colors.css && tachyons src/colors.css --minify > css/colors.min.css && tachyons src/colors.css --generate-docs --package=../../package.json > readme.md"
    },
    "style": "css/colors.css",
    "version": "3.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
