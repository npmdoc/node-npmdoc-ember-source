# npmdoc-ember-source

#### api documentation for  [ember-source (v2.12.1)](http://emberjs.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-ember-source.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ember-source) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ember-source.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ember-source)

#### A JavaScript framework for creating ambitious web applications

[![NPM](https://nodei.co/npm/ember-source.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-source)

- [https://npmdoc.github.io/node-npmdoc-ember-source/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-source/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-source/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-source/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ember-source/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ember-source/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/emberjs/ember.js/issues"
    },
    "dependencies": {
        "broccoli-funnel": "^1.0.6",
        "broccoli-merge-trees": "^1.1.4",
        "ember-cli-get-component-path-option": "^1.0.0",
        "ember-cli-normalize-entity-name": "^1.0.0",
        "ember-cli-path-utils": "^1.0.0",
        "ember-cli-string-utils": "^1.0.0",
        "ember-cli-test-info": "^1.0.0",
        "ember-cli-valid-component-name": "^1.0.0",
        "ember-cli-version-checker": "^1.1.7",
        "jquery": "^3.1.1",
        "resolve": "^1.1.7",
        "rsvp": "^3.4.0",
        "simple-dom": "^0.3.0"
    },
    "description": "A JavaScript framework for creating ambitious web applications",
    "devDependencies": {
        "aws-sdk": "~2.2.43",
        "babel-plugin-feature-flags": "^0.2.3",
        "babel-plugin-filter-imports": "~0.2.0",
        "backburner.js": "^0.3.1",
        "broccoli-rollup": "^1.0.3",
        "broccoli-string-replace": "^0.1.1",
        "broccoli-uglify-sourcemap": "^1.4.2",
        "chalk": "^1.1.1",
        "dag-map": "^2.0.1",
        "ember-cli": "2.10.0",
        "ember-cli-blueprint-test-helpers": "^0.12.0",
        "ember-cli-dependency-checker": "^1.2.0",
        "ember-cli-sauce": "^2.0.0",
        "ember-cli-yuidoc": "0.8.4",
        "ember-publisher": "0.0.7",
        "emberjs-build": "0.19.0",
        "express": "^4.5.0",
        "finalhandler": "^0.4.0",
        "git-repo-info": "^1.1.4",
        "git-repo-version": "^0.3.1",
        "github": "^0.2.3",
        "glimmer-engine": "^0.19.4",
        "glob": "^5.0.13",
        "html-differ": "^1.3.4",
        "mocha": "^2.4.5",
        "qunit-extras": "^1.5.0",
        "qunit-phantomjs-runner": "^2.2.0",
        "qunitjs": "^1.22.0",
        "route-recognizer": "^0.3.0",
        "router_js": "^1.2.4",
        "serve-static": "^1.10.0",
        "simple-dom": "^0.3.0",
        "testem": "^1.14.2"
    },
    "directories": {},
    "dist": {
        "shasum": "2d0b6fa1c9ebca668eccc7d49521584301593b7d",
        "tarball": "https://registry.npmjs.org/ember-source/-/ember-source-2.12.1.tgz"
    },
    "ember-addon": {
        "after": "ember-cli-legacy-blueprints"
    },
    "files": [
        "blueprints",
        "dist",
        "!dist/ember-tests.prod.js",
        "!dist/ember-tests.js",
        "!dist/qunit",
        "!dist/jquery",
        "!dist/tests",
        "vendor/ember",
        "index.js"
    ],
    "gitHead": "17678c6c32074849d7fab46b3ae8e1d006f6c8f4",
    "homepage": "http://emberjs.com/",
    "keywords": [
        "ember-addon"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "chancancode"
        },
        {
            "name": "ember-release"
        },
        {
            "name": "rwjblue"
        }
    ],
    "name": "ember-source",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/emberjs/ember.js.git"
    },
    "scripts": {
        "build": "ember build --environment production",
        "docs": "ember ember-cli-yuidoc",
        "pretest": "ember build",
        "release": "node scripts/release.js",
        "sauce:launch": "ember sauce:launch",
        "start": "ember serve",
        "test": "node bin/run-tests.js",
        "test:blueprints": "node node-tests/nodetest-runner.js",
        "test:sauce": "node bin/run-sauce-tests.js",
        "test:testem": "testem -f testem.dist.json"
    },
    "version": "2.12.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
