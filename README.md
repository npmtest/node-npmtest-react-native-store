# npmtest-react-native-store

#### basic test coverage for  [react-native-store (v0.4.1)](https://github.com/thewei/react-native-store)  [![npm package](https://img.shields.io/npm/v/npmtest-react-native-store.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-native-store) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-native-store.svg)](https://travis-ci.org/npmtest/node-npmtest-react-native-store)

#### A simple database base on react-native AsyncStorage.

[![NPM](https://nodei.co/npm/react-native-store.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-native-store)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-native-store/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-store/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-store/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-native-store/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-store/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-native-store/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-native-store/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-native-store/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-native-store/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-native-store/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-native-store/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-native-store/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-native-store/build/test-report.html](https://npmtest.github.io/node-npmtest-react-native-store/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-native-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-native-store/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-native-store/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-native-store/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-native-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-native-store/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-native-store/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-native-store/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "thewei"
    },
    "bugs": {
        "url": "https://github.com/thewei/react-native-store/issues"
    },
    "dependencies": {},
    "description": "A simple database base on react-native AsyncStorage.",
    "devDependencies": {
        "babel-cli": "^6.4.0",
        "babel-jest": "^6.0.1",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-stage-0": "^6.3.13",
        "jest": "^0.1.40",
        "jest-cli": "^0.8.2",
        "react-native": "^0.18.0-rc"
    },
    "directories": {},
    "dist": {
        "shasum": "dc0c61021b9b033ae3c06660ec1985771aa4300c",
        "tarball": "https://registry.npmjs.org/react-native-store/-/react-native-store-0.4.1.tgz"
    },
    "gitHead": "ef5d1687103fbdb42760d93f78cf9f25b8e4dbe8",
    "homepage": "https://github.com/thewei/react-native-store",
    "jest": {
        "scriptPreprocessor": "<rootDir>/node_modules/babel-jest",
        "testPathIgnorePatterns": [
            "/node_modules/"
        ],
        "testFileExtensions": [
            "js"
        ],
        "testPathDirs": [
            "src"
        ],
        "unmockedModulePathPatterns": [
            "promise",
            "source-map"
        ]
    },
    "keywords": [
        "react-component",
        "react-native",
        "ios",
        "android",
        "react",
        "AsyncStorage",
        "dataBase"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "thewei"
        }
    ],
    "name": "react-native-store",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/thewei/react-native-store.git"
    },
    "scripts": {
        "build": "babel src --presets es2015,stage-0 --out-dir lib",
        "test": "jest --verbose",
        "watch": "babel src --watch --presets es2015,stage-0 --out-dir lib"
    },
    "version": "0.4.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
