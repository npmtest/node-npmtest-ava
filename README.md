# npmtest-ava

#### basic test coverage for  [ava (v0.19.1)](https://ava.li)  [![npm package](https://img.shields.io/npm/v/npmtest-ava.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ava) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ava.svg)](https://travis-ci.org/npmtest/node-npmtest-ava)

#### Futuristic test runner 🚀

[![NPM](https://nodei.co/npm/ava.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ava)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ava/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ava/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ava/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ava/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ava/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ava/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ava/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ava/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ava/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ava/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ava/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ava/build/test-report.html](https://npmtest.github.io/node-npmtest-ava/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ava/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ava/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ava/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ava/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ava/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ava/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ava/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ava/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "bin": {
        "ava": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/avajs/ava/issues"
    },
    "dependencies": {
        "@ava/babel-preset-stage-4": "^1.0.0",
        "@ava/babel-preset-transform-test-files": "^3.0.0",
        "@ava/pretty-format": "^1.1.0",
        "arr-flatten": "^1.0.1",
        "array-union": "^1.0.1",
        "array-uniq": "^1.0.2",
        "arrify": "^1.0.0",
        "auto-bind": "^1.1.0",
        "ava-init": "^0.2.0",
        "babel-code-frame": "^6.16.0",
        "babel-core": "^6.17.0",
        "bluebird": "^3.0.0",
        "caching-transform": "^1.0.0",
        "chalk": "^1.0.0",
        "chokidar": "^1.4.2",
        "clean-stack": "^1.1.1",
        "clean-yaml-object": "^0.1.0",
        "cli-cursor": "^2.1.0",
        "cli-spinners": "^1.0.0",
        "cli-truncate": "^1.0.0",
        "co-with-promise": "^4.6.0",
        "code-excerpt": "^2.1.0",
        "common-path-prefix": "^1.0.0",
        "convert-source-map": "^1.2.0",
        "core-assert": "^0.2.0",
        "currently-unhandled": "^0.4.1",
        "debug": "^2.2.0",
        "diff": "^3.0.1",
        "diff-match-patch": "^1.0.0",
        "dot-prop": "^4.1.0",
        "empower-core": "^0.6.1",
        "equal-length": "^1.0.0",
        "figures": "^2.0.0",
        "find-cache-dir": "^0.1.1",
        "fn-name": "^2.0.0",
        "get-port": "^3.0.0",
        "globby": "^6.0.0",
        "has-flag": "^2.0.0",
        "hullabaloo-config-manager": "^1.0.0",
        "ignore-by-default": "^1.0.0",
        "indent-string": "^3.0.0",
        "is-ci": "^1.0.7",
        "is-generator-fn": "^1.0.0",
        "is-obj": "^1.0.0",
        "is-observable": "^0.2.0",
        "is-promise": "^2.1.0",
        "jest-diff": "19.0.0",
        "jest-snapshot": "19.0.2",
        "js-yaml": "^3.8.2",
        "last-line-stream": "^1.0.0",
        "lodash.debounce": "^4.0.3",
        "lodash.difference": "^4.3.0",
        "lodash.flatten": "^4.2.0",
        "lodash.isequal": "^4.5.0",
        "loud-rejection": "^1.2.0",
        "matcher": "^0.1.1",
        "md5-hex": "^2.0.0",
        "meow": "^3.7.0",
        "mkdirp": "^0.5.1",
        "ms": "^0.7.1",
        "multimatch": "^2.1.0",
        "observable-to-promise": "^0.5.0",
        "option-chain": "^0.1.0",
        "package-hash": "^2.0.0",
        "pkg-conf": "^2.0.0",
        "plur": "^2.0.0",
        "pretty-ms": "^2.0.0",
        "require-precompiled": "^0.1.0",
        "resolve-cwd": "^1.0.0",
        "slash": "^1.0.0",
        "source-map-support": "^0.4.0",
        "stack-utils": "^1.0.0",
        "strip-ansi": "^3.0.1",
        "strip-bom-buf": "^1.0.0",
        "supports-color": "^3.2.3",
        "time-require": "^0.1.2",
        "unique-temp-dir": "^1.0.0",
        "update-notifier": "^2.1.0"
    },
    "description": "Futuristic test runner 🚀",
    "devDependencies": {
        "babel-preset-react": "^6.5.0",
        "cli-table2": "^0.2.0",
        "coveralls": "^2.11.4",
        "delay": "^1.3.0",
        "execa": "^0.6.0",
        "flow-bin": "^0.42.0",
        "get-stream": "^3.0.0",
        "git-branch": "^0.3.0",
        "has-ansi": "^2.0.0",
        "inquirer": "^3.0.5",
        "is-array-sorted": "^1.0.0",
        "lolex": "^1.4.0",
        "nyc": "^10.0.0",
        "proxyquire": "^1.7.4",
        "rimraf": "^2.5.0",
        "signal-exit": "^3.0.0",
        "sinon": "^2.0.0",
        "source-map-fixtures": "^2.1.0",
        "tap": "^10.0.0",
        "temp-write": "^3.1.0",
        "touch": "^1.0.0",
        "typescript": "^2.2.2",
        "xo": "^0.18.0",
        "zen-observable": "^0.5.1"
    },
    "directories": {},
    "dist": {
        "shasum": "43dd82435ad19b3980ffca2488f05daab940b273",
        "tarball": "https://registry.npmjs.org/ava/-/ava-0.19.1.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "lib",
        "*.js",
        "*.js.flow",
        "types/generated.d.ts"
    ],
    "gitHead": "4cc3403b4878e0e32c8d1a2e95874223fe4cdc29",
    "homepage": "https://ava.li",
    "keywords": [
        "test",
        "runner",
        "ava",
        "concurrent",
        "parallel",
        "fast",
        "tape",
        "tap",
        "jest",
        "mocha",
        "qunit",
        "jasmine",
        "testing",
        "tdd",
        "cli-app",
        "cli",
        "assert",
        "assertion",
        "futuristic",
        "promise",
        "promises",
        "async",
        "function",
        "await",
        "generator",
        "generators",
        "yield",
        "observable",
        "observables"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "jamestalmage"
        },
        {
            "name": "jfmengels"
        },
        {
            "name": "kevva"
        },
        {
            "name": "novemberborn"
        },
        {
            "name": "sindresorhus"
        },
        {
            "name": "sotojuan"
        },
        {
            "name": "unicorn-rocket-sparkles"
        },
        {
            "name": "vdemedes"
        }
    ],
    "name": "ava",
    "nyc": {
        "reporter": [
            "html",
            "lcov",
            "text"
        ]
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/avajs/ava.git"
    },
    "scripts": {
        "make-ts": "node types/make.js",
        "prepublish": "npm run make-ts",
        "test": "xo && flow check test/flow-types && tsc -p test/ts-types && nyc tap --no-cov --timeout=150 --jobs=4 test/*.js test/reporters/*.js",
        "test-win": "tap --no-cov --reporter=classic --timeout=150 --jobs=4 test/*.js test/reporters/*.js",
        "visual": "node test/visual/run-visual-tests.js"
    },
    "typings": "types/generated.d.ts",
    "version": "0.19.1",
    "xo": {
        "esnext": true,
        "rules": {
            "import/newline-after-import": "off",
            "no-use-extend-native/no-use-extend-native": "off"
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
