# npmtest-prettier

#### basic test coverage for  [prettier (v1.2.2)](https://github.com/prettier/prettier#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-prettier.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-prettier) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-prettier.svg)](https://travis-ci.org/npmtest/node-npmtest-prettier)

#### Prettier is an opinionated JavaScript formatter

[![NPM](https://nodei.co/npm/prettier.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/prettier)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-prettier/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-prettier/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-prettier/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-prettier/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-prettier/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-prettier/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-prettier/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-prettier/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-prettier/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-prettier/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-prettier/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-prettier/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-prettier/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-prettier/build/test-report.html](https://npmtest.github.io/node-npmtest-prettier/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-prettier/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-prettier/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-prettier/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-prettier/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-prettier/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-prettier/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-prettier/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-prettier/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Long"
    },
    "bin": {
        "prettier": "./bin/prettier.js"
    },
    "bugs": {
        "url": "https://github.com/prettier/prettier/issues"
    },
    "dependencies": {
        "ast-types": "0.9.8",
        "babel-code-frame": "6.22.0",
        "babylon": "7.0.0-beta.8",
        "chalk": "1.1.3",
        "esutils": "2.0.2",
        "flow-parser": "0.43.0",
        "get-stdin": "5.0.1",
        "glob": "7.1.1",
        "jest-validate": "19.0.0",
        "minimist": "1.2.0"
    },
    "description": "Prettier is an opinionated JavaScript formatter",
    "devDependencies": {
        "diff": "3.2.0",
        "jest": "19.0.1",
        "mkdirp": "^0.5.1",
        "rimraf": "^2.6.1",
        "rollup": "0.41.1",
        "rollup-plugin-commonjs": "7.0.0",
        "rollup-plugin-json": "2.1.0",
        "rollup-plugin-node-builtins": "2.0.0",
        "rollup-plugin-node-globals": "1.1.0",
        "rollup-plugin-node-resolve": "2.0.0",
        "typescript": "2.2.1",
        "typescript-eslint-parser": "git://github.com/eslint/typescript-eslint-parser.git#bfb1506c48b625871ffeb67dbec7941d460f8941"
    },
    "directories": {},
    "dist": {
        "shasum": "22d17c1132faaaea1f1d4faea31f19f7a1959f3e",
        "tarball": "https://registry.npmjs.org/prettier/-/prettier-1.2.2.tgz"
    },
    "gitHead": "88e004184b67cc073d43b2b6a152b03240705f84",
    "homepage": "https://github.com/prettier/prettier#readme",
    "jest": {
        "setupFiles": [
            "<rootDir>/tests_config/run_spec.js"
        ],
        "snapshotSerializers": [
            "<rootDir>/tests_config/raw-serializer.js"
        ],
        "testRegex": "jsfmt\\.spec\\.js$",
        "testPathIgnorePatterns": [
            "tests/new_react",
            "tests/more_react"
        ]
    },
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "jlongster"
        },
        {
            "name": "vjeux"
        }
    ],
    "name": "prettier",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/prettier/prettier.git"
    },
    "scripts": {
        "build:docs": "rollup -c docs/rollup.config.js",
        "format": "./bin/prettier.js --write",
        "format:all": "npm run format -- index.js src/*.js bin/*.js",
        "format:single": "npm run format -- src/printer.js",
        "test": "jest"
    },
    "version": "1.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
