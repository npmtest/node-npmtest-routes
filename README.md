# npmtest-routes

#### basic test coverage for  [routes (v2.1.0)](https://github.com/aaronblohowiak/routes.js)  [![npm package](https://img.shields.io/npm/v/npmtest-routes.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-routes) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-routes.svg)](https://travis-ci.org/npmtest/node-npmtest-routes)

#### Minimalist route matching for javascript

[![NPM](https://nodei.co/npm/routes.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/routes)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-routes/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-routes/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-routes/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-routes/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-routes/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-routes/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-routes/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-routes/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-routes/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-routes/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-routes/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-routes/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-routes/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-routes/build/test-report.html](https://npmtest.github.io/node-npmtest-routes/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-routes/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-routes/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-routes/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-routes/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-routes/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-routes/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-routes/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-routes/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Aaron Blohowiak",
        "url": "http://github.com/aaronblohowiak"
    },
    "bugs": {
        "url": "https://github.com/aaronblohowiak/routes.js/issues"
    },
    "dependencies": {},
    "description": "Minimalist route matching for javascript",
    "devDependencies": {
        "browserify": "^3.30.4"
    },
    "directories": {
        "lib": "."
    },
    "dist": {
        "shasum": "475571192a48f99b6c065dd926bb75e8ae83e8a2",
        "tarball": "https://registry.npmjs.org/routes/-/routes-2.1.0.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "f85efed8b5a626130a4a549fdf262f8e885ebb6d",
    "homepage": "https://github.com/aaronblohowiak/routes.js",
    "main": "dist/routes",
    "maintainers": [
        {
            "name": "aaronblohowiak"
        },
        {
            "name": "raynos"
        }
    ],
    "name": "routes",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/aaronblohowiak/routes.js.git"
    },
    "scripts": {
        "prepublish": "mkdir -p dist/ && browserify --require ./index --standalone routes > dist/routes.js",
        "test": "make test"
    },
    "version": "2.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
