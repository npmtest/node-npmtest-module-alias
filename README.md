# npmtest-module-alias

#### basic test coverage for  [module-alias (v2.0.0)](https://github.com/ilearnio/module-alias)  [![npm package](https://img.shields.io/npm/v/npmtest-module-alias.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-module-alias) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-module-alias.svg)](https://travis-ci.org/npmtest/node-npmtest-module-alias)

#### Create aliases of directories and register custom module paths in NodeJS like a boss!

[![NPM](https://nodei.co/npm/module-alias.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/module-alias)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-module-alias/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-module-alias/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-module-alias/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-module-alias/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-module-alias/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-module-alias/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-module-alias/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-module-alias/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-module-alias/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-module-alias/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-module-alias/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-module-alias/build/test-report.html](https://npmtest.github.io/node-npmtest-module-alias/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-module-alias/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-module-alias/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-module-alias/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-module-alias/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-module-alias/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-module-alias/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-module-alias/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-module-alias/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nick Gavrilov"
    },
    "bugs": {
        "url": "https://github.com/ilearnio/module-alias/issues"
    },
    "dependencies": {},
    "description": "Create aliases of directories and register custom module paths in NodeJS like a boss!",
    "devDependencies": {
        "chai": "^3.5.0",
        "hello-world-classic": "github:ilearnio/hello-world-classic",
        "mocha": "^2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "9bff2cba6eb181dac8e379d69fe34b066a970988",
        "tarball": "https://registry.npmjs.org/module-alias/-/module-alias-2.0.0.tgz"
    },
    "files": [
        "index.js",
        "register.js",
        "README.md"
    ],
    "gitHead": "3bc8a84c4257d6e4b3c18b2798048d40270539ef",
    "homepage": "https://github.com/ilearnio/module-alias",
    "keywords": [
        "extend",
        "modules",
        "node",
        "path",
        "resolve"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ilearnio"
        }
    ],
    "name": "module-alias",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ilearnio/module-alias.git"
    },
    "scripts": {
        "lint": "standard src",
        "test": "npm run lint && npm run testonly",
        "testonly": "NODE_ENV=test mocha test/specs.js",
        "testonly-watch": "NODE_ENV=test mocha -w test/specs.js"
    },
    "version": "2.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
