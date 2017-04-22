# npmtest-swaggerize-express

#### basic test coverage for  [swaggerize-express (v4.0.5)](https://github.com/krakenjs/swaggerize-express#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-swaggerize-express.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-swaggerize-express) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-swaggerize-express.svg)](https://travis-ci.org/npmtest/node-npmtest-swaggerize-express)

#### Design-driven apis with swagger 2.0 and express.

[![NPM](https://nodei.co/npm/swaggerize-express.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/swaggerize-express)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-swaggerize-express/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-swaggerize-express/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-swaggerize-express/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-swaggerize-express/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-swaggerize-express/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-swaggerize-express/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-swaggerize-express/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-swaggerize-express/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-swaggerize-express/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-swaggerize-express/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-swaggerize-express/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-swaggerize-express/build/test-report.html](https://npmtest.github.io/node-npmtest-swaggerize-express/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-swaggerize-express/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-swaggerize-express/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-swaggerize-express/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-swaggerize-express/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-swaggerize-express/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-swaggerize-express/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-swaggerize-express/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-swaggerize-express/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Trevor Livingston"
    },
    "bugs": {
        "url": "http://github.com/krakenjs/swaggerize-express/issues"
    },
    "dependencies": {
        "async": "^0.9.0",
        "caller": "^0.0.1",
        "core-util-is": "^1.0.1",
        "debuglog": "^1.0.1",
        "js-yaml": "^3.2.6",
        "swaggerize-routes": "^1.0.0"
    },
    "description": "Design-driven apis with swagger 2.0 and express.",
    "devDependencies": {
        "body-parser": "^1.7.0",
        "express": "^4.6.1",
        "istanbul": "^0.2.3",
        "jshint": "^2.4.1",
        "supertest": "^0.13.0",
        "tape": "^2.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "16ce89726051c3e1263879e1b9190b4ecb301740",
        "tarball": "https://registry.npmjs.org/swaggerize-express/-/swaggerize-express-4.0.5.tgz"
    },
    "engines": {
        "node": "0.10.x"
    },
    "gitHead": "dfc8ccce13a0a6196a46b7f6c6e001176e647523",
    "homepage": "https://github.com/krakenjs/swaggerize-express#readme",
    "keywords": [
        "swagger",
        "swagger 2.0",
        "swagger-node",
        "swagger-express",
        "swagger-ui",
        "express",
        "node",
        "node.js",
        "rest",
        "restful",
        "service",
        "api"
    ],
    "licenses": [
        {
            "type": "Apache 2.0",
            "url": "http://www.apache.org/licenses/LICENSE-2.0.html"
        }
    ],
    "main": "./lib/index",
    "maintainers": [
        {
            "name": "tlivings"
        }
    ],
    "name": "swaggerize-express",
    "optionalDependencies": {},
    "peerDependencies": {
        "express": "^4.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/krakenjs/swaggerize-express.git"
    },
    "scripts": {
        "cover": "istanbul cover tape -- test/*.js",
        "lint": "jshint -c .jshintrc lib/*.js",
        "test": "tape test/*.js"
    },
    "version": "4.0.5",
    "warnings": [
        {
            "code": "ENOTSUP",
            "required": {
                "node": "0.10.x"
            },
            "pkgid": "swaggerize-express@4.0.5"
        },
        {
            "code": "ENOTSUP",
            "required": {
                "node": "0.10.x"
            },
            "pkgid": "swaggerize-express@4.0.5"
        }
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
