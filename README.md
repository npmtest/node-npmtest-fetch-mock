# npmtest-fetch-mock

#### basic test coverage for  [fetch-mock (v5.10.0)](http://www.wheresrhys.co.uk/fetch-mock)  [![npm package](https://img.shields.io/npm/v/npmtest-fetch-mock.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fetch-mock) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fetch-mock.svg)](https://travis-ci.org/npmtest/node-npmtest-fetch-mock)

#### Mock http requests made using fetch (or isomorphic-fetch)

[![NPM](https://nodei.co/npm/fetch-mock.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fetch-mock)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fetch-mock/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fetch-mock/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fetch-mock/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fetch-mock/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fetch-mock/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fetch-mock/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fetch-mock/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fetch-mock/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fetch-mock/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fetch-mock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fetch-mock/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fetch-mock/build/test-report.html](https://npmtest.github.io/node-npmtest-fetch-mock/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fetch-mock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fetch-mock/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fetch-mock/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fetch-mock/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fetch-mock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fetch-mock/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fetch-mock/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fetch-mock/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "fetch-mock",
    "version": "5.10.0",
    "description": "Mock http requests made using fetch (or isomorphic-fetch)",
    "main": "src/server.js",
    "browser": "es5/client.js",
    "scripts": {
        "test": "make test",
        "browserify": "browserify -s fetchMock es5/client.js > es5/client-browserified.js",
        "prepublish": "babel src --out-dir es5 --plugins transform-object-assign --presets es2015 && npm run browserify"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/wheresrhys/fetch-mock.git"
    },
    "keywords": [
        "fetch",
        "http",
        "mock",
        "testing",
        "spy",
        "ajax",
        "xhr"
    ],
    "author": "Rhys Evans",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/wheresrhys/fetch-mock/issues"
    },
    "homepage": "http://www.wheresrhys.co.uk/fetch-mock",
    "dependencies": {
        "glob-to-regexp": "^0.3.0",
        "node-fetch": "^1.3.3",
        "path-to-regexp": "^1.7.0"
    },
    "devDependencies": {
        "babel": "^6.0.15",
        "babel-cli": "^6.1.2",
        "babel-plugin-transform-object-assign": "^6.8.0",
        "babel-preset-es2015": "^6.1.2",
        "babelify": "^7.3.0",
        "bluebird": "^3.4.6",
        "browserify": "^13.1.0",
        "chai": "^2.3.0",
        "eslint": "^1.10.3",
        "karma": "^1.3.0",
        "karma-browserify": "^5.1.0",
        "karma-chai": "^0.1.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-firefox-launcher": "^1.0.0",
        "karma-mocha": "^1.2.0",
        "karma-phantomjs-launcher": "^1.0.2",
        "mocha": "^2.2.4",
        "mockery": "^1.4.0",
        "sinon": "^1.17.0",
        "watchify": "^3.7.0",
        "whatwg-fetch": "^0.10.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
