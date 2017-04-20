# npmtest-ical-generator

#### basic test coverage for  ical-generator (v0.2.9)  [![npm package](https://img.shields.io/npm/v/npmtest-ical-generator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ical-generator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ical-generator.svg)](https://travis-ci.org/npmtest/node-npmtest-ical-generator)

#### ical-generator is a small piece of code which generates ical calendar files

[![NPM](https://nodei.co/npm/ical-generator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ical-generator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ical-generator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ical-generator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ical-generator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ical-generator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ical-generator/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ical-generator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ical-generator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ical-generator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ical-generator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ical-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ical-generator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ical-generator/build/test-report.html](https://npmtest.github.io/node-npmtest-ical-generator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ical-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ical-generator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ical-generator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ical-generator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ical-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ical-generator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ical-generator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ical-generator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ical-generator",
    "description": "ical-generator is a small piece of code which generates ical calendar files",
    "author": "Sebastian Pekarek <mail@sebbo.net>",
    "version": "0.2.9",
    "bugs": {
        "url": "http://github.com/sebbo2002/ical-generator/issues"
    },
    "dependencies": {},
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-contrib-jshint": "^0.11.0",
        "grunt-contrib-watch": "^0.6.1",
        "istanbul": "^0.3.0",
        "mocha": "^1.20.1",
        "portfinder": "^0.2.1"
    },
    "scripts": {
        "test": "grunt && istanbul cover _mocha -- -R spec --no-colors"
    },
    "tonicExampleFilename": "./example/example_tonic.js",
    "preferGlobal": false,
    "main": "./lib/index.js",
    "repository": {
        "type": "git",
        "url": "http://github.com/sebbo2002/ical-generator.git"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
