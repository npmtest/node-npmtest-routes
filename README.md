# test coverage for  [routes (v2.1.0)](https://github.com/aaronblohowiak/routes.js)  [![npm package](https://img.shields.io/npm/v/npmtest-routes.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-routes) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-routes.svg)](https://travis-ci.org/npmtest/node-npmtest-routes)
#### Minimalist route matching for javascript

[![NPM](https://nodei.co/npm/routes.png?downloads=true)](https://www.npmjs.com/package/routes)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-routes/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-routes/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-routes/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-routes/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-routes/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-routes/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-routes/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-routes/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-routes/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-routes/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-routes%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-routes/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-routes/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-routes%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-routes/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-routes/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-routes/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Aaron Blohowiak",
        "email": "aaron.blohowiak@gmail.com",
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
            "name": "aaronblohowiak",
            "email": "aaron.blohowiak@gmail.com"
        },
        {
            "name": "raynos",
            "email": "raynos2@gmail.com"
        }
    ],
    "name": "routes",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/aaronblohowiak/routes.js.git"
    },
    "scripts": {
        "prepublish": "mkdir -p dist/ && browserify --require ./index --standalone routes > dist/routes.js",
        "test": "make test"
    },
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
