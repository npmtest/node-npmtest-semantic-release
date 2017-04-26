# npmtest-semantic-release

#### basic test coverage for  [semantic-release (v6.3.2)](https://github.com/semantic-release/semantic-release/tree/next#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-semantic-release.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-semantic-release) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-semantic-release.svg)](https://travis-ci.org/npmtest/node-npmtest-semantic-release)

#### automated semver compliant package publishing

[![NPM](https://nodei.co/npm/semantic-release.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/semantic-release)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-semantic-release/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-semantic-release/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-semantic-release/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-semantic-release/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-semantic-release/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-semantic-release/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-semantic-release/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-semantic-release/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-semantic-release/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-semantic-release/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-semantic-release/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-semantic-release/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-semantic-release/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-semantic-release/build/test-report.html](https://npmtest.github.io/node-npmtest-semantic-release/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-semantic-release/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-semantic-release/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-semantic-release/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-semantic-release/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-semantic-release/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-semantic-release/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-semantic-release/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-semantic-release/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stephan Bönnemann",
        "url": "http://boennemann.me"
    },
    "bin": {
        "semantic-release": "bin/semantic-release.js"
    },
    "bugs": {
        "url": "https://github.com/semantic-release/semantic-release/issues"
    },
    "czConfig": {
        "path": "node_modules/cz-conventional-changelog/"
    },
    "dependencies": {
        "@bahmutov/parse-github-repo-url": "^0.1.0",
        "@semantic-release/commit-analyzer": "^2.0.0",
        "@semantic-release/condition-travis": "^5.0.2",
        "@semantic-release/error": "^1.0.0",
        "@semantic-release/last-release-npm": "^1.2.1",
        "@semantic-release/release-notes-generator": "^2.0.0",
        "git-head": "^1.2.1",
        "github": "^0.2.4",
        "lodash": "^4.0.0",
        "nerf-dart": "^1.0.0",
        "nopt": "^3.0.3",
        "normalize-package-data": "^2.3.4",
        "npmconf": "^2.1.2",
        "npmlog": "^4.0.0",
        "require-relative": "^0.8.7",
        "run-auto": "^2.0.0",
        "run-series": "^1.1.3",
        "semver": "^5.0.3"
    },
    "description": "automated semver compliant package publishing",
    "devDependencies": {
        "coveralls": "^2.11.4",
        "cz-conventional-changelog": "^1.1.4",
        "mkdirp": "^0.5.1",
        "nixt": "^0.5.0",
        "nock": "^8.0.0",
        "npm-registry-couchapp": "^2.6.11",
        "nyc": "^7.0.0",
        "proxyquire": "^1.7.3",
        "rimraf": "^2.5.0",
        "standard": "^7.0.1",
        "tap": "^6.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "224ec4540724a1646cc6dba4a9d2cd6bc8b68311",
        "tarball": "https://registry.npmjs.org/semantic-release/-/semantic-release-6.3.2.tgz"
    },
    "engines": {
        "node": ">=0.10",
        "npm": ">=2"
    },
    "files": [
        "bin",
        "src"
    ],
    "gitHead": "2be6e5d34a4c89a74a8a0bd40a6706d3705be448",
    "homepage": "https://github.com/semantic-release/semantic-release/tree/next#readme",
    "keywords": [
        "author",
        "automation",
        "changelog",
        "module",
        "package",
        "publish",
        "release",
        "semver",
        "version"
    ],
    "license": "MIT",
    "main": "bin/semantic-release.js",
    "maintainers": [
        {
            "name": "boennemann"
        },
        {
            "name": "christophwitzko"
        },
        {
            "name": "semantic-release-bot"
        }
    ],
    "name": "semantic-release",
    "optionalDependencies": {},
    "publishConfig": {
        "tag": "next"
    },
    "release": {
        "branch": "caribou"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/semantic-release/semantic-release.git"
    },
    "scripts": {
        "coverage": "nyc report",
        "coverage:upload": "npm run coverage -s -- --reporter=text-lcov | coveralls",
        "pretest": "standard",
        "semantic-release": "./bin/semantic-release.js pre && npm publish && ./bin/semantic-release.js post",
        "test": "npm run test:unit && npm run test:integration",
        "test:integration": "tap --no-cov test/scenarios/*.js",
        "test:unit": "nyc tap --no-cov test/specs/*.js"
    },
    "version": "6.3.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
