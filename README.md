# npmtest-ember-prerender

#### basic test coverage for  [ember-prerender (v2.5.5)](https://github.com/zipfworks/ember-prerender)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-prerender.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-prerender) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-prerender.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-prerender)

#### Render static HTML from your Ember.js web apps on the server for SEO and other purposes.

[![NPM](https://nodei.co/npm/ember-prerender.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-prerender)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-prerender/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-prerender/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-prerender/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-prerender/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-prerender/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-prerender/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-prerender/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-prerender/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-prerender/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-prerender/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-prerender/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-prerender/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-prerender/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-prerender/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-prerender/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-prerender/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-prerender/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-prerender/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-prerender/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-prerender/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-prerender/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ember-prerender",
    "summary": "Static HTML rendering for Ember.js",
    "description": "Render static HTML from your Ember.js web apps on the server for SEO and other purposes.",
    "version": "2.5.5",
    "author": "Brian Stanback",
    "repository": {
        "type": "git",
        "url": "https://github.com/zipfworks/ember-prerender"
    },
    "dependencies": {
        "cache-manager": "^0.19.0",
        "cli-color": ">= 0.3 < 0.4",
        "lodash": ">= 2.4 < 2.5",
        "minimize": "^1.3.3",
        "mongodb": "^2.0.25",
        "phantom": "^0.7.2",
        "phantomjs": ">= 1.9 < 1.10",
        "pretty": ">= 0.1 < 0.2",
        "request": ">= 2.0 < 3.0"
    },
    "optionalDependencies": {
        "aws-sdk": ">= 2.0 < 3.0",
        "chromedriver": "^2.10.0-1",
        "jsdom": "1.0.2",
        "selenium-webdriver": "^2.43.5"
    },
    "bin": {
        "ember-prerender": "bin/ember-prerender"
    },
    "scripts": {
        "start": "node server.js"
    },
    "bugs": {
        "url": "https://github.com/zipfworks/ember-prerender/issues"
    },
    "homepage": "https://github.com/zipfworks/ember-prerender",
    "main": "index.js",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
