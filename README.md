# test coverage for  [webpack-bundle-analyzer (v2.3.1)](https://github.com/th0r/webpack-bundle-analyzer)  [![npm package](https://img.shields.io/npm/v/npmtest-webpack-bundle-analyzer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webpack-bundle-analyzer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webpack-bundle-analyzer.svg)](https://travis-ci.org/npmtest/node-npmtest-webpack-bundle-analyzer)
#### Webpack plugin and CLI utility that represents bundle content as convenient interactive zoomable treemap

[![NPM](https://nodei.co/npm/webpack-bundle-analyzer.png?downloads=true)](https://www.npmjs.com/package/webpack-bundle-analyzer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webpack-bundle-analyzer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-bundle-analyzer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-bundle-analyzer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webpack-bundle-analyzer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-bundle-analyzer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webpack-bundle-analyzer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webpack-bundle-analyzer/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-bundle-analyzer/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-webpack-bundle-analyzer/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-webpack-bundle-analyzer/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-webpack-bundle-analyzer%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webpack-bundle-analyzer/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webpack-bundle-analyzer/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-webpack-bundle-analyzer%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webpack-bundle-analyzer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-webpack-bundle-analyzer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-webpack-bundle-analyzer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Yury Grunin",
        "email": "grunin.ya@ya.ru"
    },
    "bin": {
        "webpack-bundle-analyzer": "lib/bin/analyzer.js"
    },
    "bugs": {
        "url": "https://github.com/th0r/webpack-bundle-analyzer/issues"
    },
    "changelog": "https://github.com/th0r/webpack-bundle-analyzer/blob/master/CHANGELOG.md",
    "dependencies": {
        "acorn": "^4.0.11",
        "chalk": "^1.1.3",
        "commander": "^2.9.0",
        "ejs": "^2.5.5",
        "express": "^4.14.1",
        "filesize": "^3.5.4",
        "gzip-size": "^3.0.0",
        "lodash": "^4.17.4",
        "mkdirp": "^0.5.1",
        "opener": "^1.4.2"
    },
    "description": "Webpack plugin and CLI utility that represents bundle content as convenient interactive zoomable treemap",
    "devDependencies": {
        "babel-core": "6.22.1",
        "babel-eslint": "7.1.1",
        "babel-loader": "6.2.10",
        "babel-plugin-transform-react-jsx": "6.22.0",
        "babel-plugin-transform-runtime": "6.22.0",
        "babel-polyfill": "6.22.0",
        "babel-preset-es2015": "6.22.0",
        "babel-preset-stage-2": "6.22.0",
        "chai": "3.5.0",
        "chai-subset": "1.4.0",
        "classnames": "2.2.5",
        "css-loader": "0.26.1",
        "del": "2.2.2",
        "eslint": "3.15.0",
        "eslint-plugin-react": "6.9.0",
        "exports-loader": "0.6.3",
        "gulp": "3.9.1",
        "gulp-babel": "6.1.2",
        "gulp-plumber": "1.1.0",
        "gulp-util": "3.0.8",
        "gulp-watch": "4.3.11",
        "mocha": "3.2.0",
        "nightmare": "2.9.1",
        "preact": "7.2.0",
        "sinon": "1.17.7",
        "stream-combiner2": "1.1.1",
        "style-loader": "0.13.1",
        "webpack": "2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "d97f8aadbcce68fc865c5787741d8549359a25cd",
        "tarball": "https://registry.npmjs.org/webpack-bundle-analyzer/-/webpack-bundle-analyzer-2.3.1.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "files": [
        "public",
        "lib",
        "src",
        "views"
    ],
    "gitHead": "2e3dc36ad4b20241f543a48bd5322b611d19dda8",
    "homepage": "https://github.com/th0r/webpack-bundle-analyzer",
    "keywords": [
        "webpack",
        "bundle",
        "analyzer",
        "modules",
        "size",
        "interactive",
        "chart",
        "treemap",
        "zoomable",
        "zoom"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "th0r",
            "email": "grunin.ya@ya.ru"
        }
    ],
    "name": "webpack-bundle-analyzer",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/th0r/webpack-bundle-analyzer.git"
    },
    "scripts": {
        "build": "gulp build",
        "lint": "eslint --ext js,jsx .",
        "npm-publish": "npm run lint && npm run build && npm test && npm publish",
        "start": "gulp watch",
        "test": "mocha --compilers js:babel-core/register -r babel-polyfill",
        "test-dev": "mocha --watch --compilers js:babel-core/register -r babel-polyfill"
    },
    "version": "2.3.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
