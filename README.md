# npmtest-angular-translate

#### basic test coverage for  [angular-translate (v2.15.1)](https://github.com/angular-translate/angular-translate#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-angular-translate.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-angular-translate) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-angular-translate.svg)](https://travis-ci.org/npmtest/node-npmtest-angular-translate)

#### A translation module for AngularJS

[![NPM](https://nodei.co/npm/angular-translate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/angular-translate)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-angular-translate/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular-translate/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-angular-translate/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-angular-translate/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-angular-translate/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-angular-translate/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-angular-translate/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-angular-translate/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-angular-translate/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-angular-translate/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-angular-translate/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular-translate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-angular-translate/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-angular-translate/build/test-report.html](https://npmtest.github.io/node-npmtest-angular-translate/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-angular-translate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-angular-translate/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-angular-translate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-angular-translate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-angular-translate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-angular-translate/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-angular-translate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-angular-translate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Pascal Precht"
    },
    "bugs": {
        "url": "https://github.com/angular-translate/angular-translate/issues"
    },
    "contributors": [
        {
            "name": "Jan Philipp",
            "url": "https://github.com/knalli"
        },
        {
            "name": "Max Prichinenko"
        },
        {
            "name": "Thorsten S"
        }
    ],
    "dependencies": {
        "angular": ">=1.2.26 <=1.6"
    },
    "description": "A translation module for AngularJS",
    "devDependencies": {
        "adm-zip": "^0.4.7",
        "body-parser": "^1.16.0",
        "bower": "^1.7.9",
        "errorhandler": "^1.5.0",
        "express": "^4.14.1",
        "express-session": "^1.15.0",
        "fbjs-scripts": "^0.7.1",
        "grunt": "~1.0.1",
        "grunt-bower-install-simple": "^1.0.3",
        "grunt-bump": "^0.8.0",
        "grunt-cli": "^1.2.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-concat": "^1.0.0",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-uglify": "^2.0.0",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-conventional-changelog": "^6.1.0",
        "grunt-file-append": "0.0.6",
        "grunt-karma": "^2.0.0",
        "grunt-ng-annotate": "^3.0.0",
        "grunt-ngdocs": "~0.2.5",
        "grunt-parallel": "^0.5.1",
        "grunt-umd": "^2.3.3",
        "grunt-version": "^1.0.0",
        "inquirer": "^3.0.1",
        "jasmine-core": "^2.1.3",
        "karma": "^1.3.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-coverage": "^1.1.1",
        "karma-firefox-launcher": "~1.0.0",
        "karma-jasmine": "^1.0.2",
        "karma-phantomjs-launcher": "^1.0.0",
        "load-grunt-tasks": "^3.4.1",
        "local-web-server": "^1.2.6",
        "method-override": "^2.3.7",
        "morgan": "^1.8.0",
        "multer": "^1.3.0",
        "phantomjs-prebuilt": "^2.1.4",
        "plato": "^1.5.0",
        "publish-release": "^1.3.3",
        "pug": "^2.0.0-beta11",
        "serve-favicon": "^2.3.2",
        "tar.gz": "^1.0.5"
    },
    "devEngines": {
        "node": ">=6.9",
        "npm": ">=3"
    },
    "directories": {},
    "dist": {
        "shasum": "920f7d2b877819e1c0fa881781b9b675f36480ce",
        "tarball": "https://registry.npmjs.org/angular-translate/-/angular-translate-2.15.1.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "cc6d122e6f34e15806d30eef6b7886172e3a31e7",
    "homepage": "https://github.com/angular-translate/angular-translate#readme",
    "keywords": [
        "angular-translate",
        "angular",
        "AngularJS",
        "translation"
    ],
    "license": "MIT",
    "main": "dist/angular-translate.js",
    "maintainers": [
        {
            "name": "knalli"
        }
    ],
    "name": "angular-translate",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/angular-translate/angular-translate.git"
    },
    "scripts": {
        "build": "npm run-script -s check-env && grunt build",
        "build-site": "npm run -s build-site-all-languages; npm run -s build-site-plato-report",
        "build-site-all-languages": "./build_tools/generate_site.sh",
        "build-site-by-language": "./build_tools/generate_site_by_language.sh",
        "build-site-plato-report": "rm -rf ./site/plato && plato -d plato -l .jshintrc src/*.js src/**/*.js && mv plato site",
        "check-env": "node node_modules/fbjs-scripts/node/check-dev-engines.js package.json",
        "clean-test-scopes": "for f in test_scopes/*; do (cd $f; rm -rf bower_components); done",
        "compile": "npm run-script -s check-env && grunt compile",
        "lint": "grunt lint",
        "prepublish": "bower install",
        "shipit": "npm run-script -s check-env && bower install && bower update && grunt prepare-release",
        "start-demo": "node build_tools/server.js",
        "test": "npm run-script -s check-env && grunt install-test && grunt test",
        "test-headless": "npm run-script -s check-env && grunt test-headless",
        "test-scopes": "npm run-script -s check-env && grunt install-test && for f in test_scopes/*; do TEST_SCOPE=\"'basename $f'\" grunt test; done",
        "upload-github-release": "node build_tools/upload-github-release.js"
    },
    "version": "2.15.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
