# test coverage for  [redux-form (v6.6.2)](https://redux-form.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-redux-form.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-redux-form) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-redux-form.svg)](https://travis-ci.org/npmtest/node-npmtest-redux-form)
#### A higher order component decorator for forms using Redux and React

[![NPM](https://nodei.co/npm/redux-form.png?downloads=true)](https://www.npmjs.com/package/redux-form)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-redux-form/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-form/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-redux-form/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-redux-form/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-redux-form/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-redux-form/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-redux-form/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-form/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-redux-form/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-redux-form/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-redux-form%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-redux-form/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-form/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-redux-form%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-form/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-redux-form/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-redux-form/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Erik Rasmussen",
        "email": "rasmussenerik@gmail.com",
        "url": "http://github.com/erikras"
    },
    "bugs": {
        "url": "https://github.com/erikras/redux-form/issues"
    },
    "dependencies": {
        "deep-equal": "^1.0.1",
        "es6-error": "^4.0.0",
        "hoist-non-react-statics": "^1.2.0",
        "invariant": "^2.2.2",
        "is-promise": "^2.1.0",
        "lodash": "^4.17.3",
        "lodash-es": "^4.17.3"
    },
    "description": "A higher order component decorator for forms using Redux and React",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-core": "^6.21.0",
        "babel-eslint": "^7.2.1",
        "babel-loader": "^6.2.10",
        "babel-plugin-istanbul": "^4.1.1",
        "babel-plugin-lodash": "^3.2.11",
        "babel-plugin-syntax-async-functions": "^6.13.0",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.18.0",
        "babel-plugin-transform-regenerator": "^6.21.0",
        "babel-preset-es2015-no-commonjs": "^0.0.2",
        "babel-preset-react": "^6.16.0",
        "babel-preset-stage-2": "^6.18.0",
        "babel-register": "^6.18.0",
        "codecov.io": "^0.1.6",
        "cross-env": "^3.1.3",
        "eslint": "^3.17.1",
        "eslint-config-react-app": "^0.6.2",
        "eslint-plugin-flowtype": "^2.30.4",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-react": "^6.10.3",
        "expect": "^1.20.2",
        "expect-element": "^1.1.1",
        "expect-immutable": "^0.0.3",
        "expect-predicate": "^1.0.0",
        "flux-standard-action": "^1.0.0",
        "jsdom": "^9.9.1",
        "lodash-webpack-plugin": "^0.11.2",
        "mocha": "^3.2.0",
        "nyc": "^10.2.0",
        "react": "^15.4.1",
        "react-addons-test-utils": "^15.4.1",
        "react-dom": "^15.4.1",
        "react-redux": "^5.0.1",
        "redux": "^3.6.0",
        "redux-immutablejs": "^0.0.8",
        "rifraf": "^2.0.3",
        "rimraf": "^2.5.4",
        "stringstream": "^0.0.5",
        "tmp": "0.0.31",
        "webpack": "^2.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "51102430a38b4d85529290a881bc1efb54f580ae",
        "tarball": "https://registry.npmjs.org/redux-form/-/redux-form-6.6.2.tgz"
    },
    "files": [
        "README.md",
        "es",
        "lib",
        "dist",
        "immutable.js"
    ],
    "gitHead": "14cf2a9f8a3461ff00780f5a5a47b701f1795d96",
    "homepage": "https://redux-form.com/",
    "jsnext:main": "./es/index.js",
    "keywords": [
        "react",
        "reactjs",
        "flux",
        "redux",
        "react-redux",
        "redux-form",
        "form",
        "decorator"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "erikras",
            "email": "rasmussenerik@gmail.com"
        }
    ],
    "module": "./es/index.js",
    "name": "redux-form",
    "npmFileMap": [
        {
            "basePath": "/dist/",
            "files": [
                "*.js"
            ]
        }
    ],
    "npmName": "redux-form",
    "nyc": {
        "include": [
            "src/**/*.js"
        ],
        "sourceMap": false,
        "instrument": false
    },
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.0.0",
        "react-redux": "^4.3.0 || ^5.0.0",
        "redux": "^3.0.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/erikras/redux-form.git"
    },
    "scripts": {
        "build": "npm run build:lib && npm run build:es && npm run build:umd && npm run build:umd:min",
        "build:es": "cross-env BABEL_ENV=es babel src --out-dir es",
        "build:lib": "babel src --out-dir lib",
        "build:umd": "cross-env NODE_ENV=development webpack src/index.js dist/redux-form.js",
        "build:umd:min": "cross-env NODE_ENV=production webpack src/index.js dist/redux-form.min.js",
        "clean": "rimraf dist lib",
        "example": "npm --prefix ./examples/$form install && npm --prefix ./examples/$form start",
        "example:asyncValidation": "form=asyncValidation npm run example",
        "example:fieldArrays": "form=fieldArrays npm run example",
        "example:fieldLevelValidation": "form=fieldLevelValidation npm run example",
        "example:immutable": "form=immutable npm run example",
        "example:initializeFromState": "form=initializeFromState npm run example",
        "example:material-ui": "form=material-ui npm run example",
        "example:normalizing": "form=normalizing npm run example",
        "example:react-widgets": "form=react-widgets npm run example",
        "example:selectingFormValues": "form=selectingFormValues npm run example",
        "example:simple": "form=simple npm run example",
        "example:submitValidation": "form=submitValidation npm run example",
        "example:syncValidation": "form=syncValidation npm run example",
        "example:wizard": "form=wizard npm run example",
        "lint": "eslint src",
        "prepublish": "npm run test && npm run clean && npm run build",
        "test": "mocha --compilers js:babel-register --recursive --recursive \"src/**/__tests__/*\" --require src/__tests__/setup.js",
        "test:codecov": "cat ./coverage/lcov.info | ./node_modules/codecov.io/bin/codecov.io.js",
        "test:cov": "cross-env NODE_ENV=test nyc --reporter=lcov --reporter=text npm test",
        "test:watch": "npm test -- --watch"
    },
    "version": "6.6.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
