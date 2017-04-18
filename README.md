# npmdoc-react-portal

api documentation for  [react-portal (v3.0.0)](https://github.com/tajo/react-portal#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-portal.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-portal) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-portal.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-portal)
#### React component for transportation of modals, lightboxes, loading bars... to document.body

[![NPM](https://nodei.co/npm/react-portal.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-portal)

- [https://npmdoc.github.io/node-npmdoc-react-portal/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-portal/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-portal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-portal/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-portal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-portal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vojtech Miksu"
    },
    "bugs": {
        "url": "https://github.com/tajo/react-portal/issues"
    },
    "dependencies": {},
    "description": "React component for transportation of modals, lightboxes, loading bars... to document.body",
    "devDependencies": {
        "babel-cli": "^6.8.0",
        "babel-core": "^6.8.0",
        "babel-eslint": "^6.0.4",
        "babel-loader": "^6.2.1",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.3.13",
        "babel-preset-react-hmre": "^1.0.1",
        "babel-register": "^6.8.0",
        "cross-env": "^1.0.7",
        "enzyme": "^2.3.0",
        "eslint": "^2.9.0",
        "eslint-config-airbnb": "^9.0.1",
        "eslint-plugin-import": "^1.8.0",
        "eslint-plugin-jsx-a11y": "^1.2.0",
        "eslint-plugin-react": "^5.1.1",
        "express": "^4.13.3",
        "jsdom": "^9.0.0",
        "mocha": "^2.3.4",
        "mocha-eslint": "^2.0.2",
        "react": "^15.2.0",
        "react-addons-test-utils": "^15.2.0",
        "react-dom": "^15.2.0",
        "rimraf": "^2.5.0",
        "sinon": "^1.17.4",
        "tween.js": "^16.3.1",
        "webpack": "^1.13.0",
        "webpack-dev-middleware": "^1.6.1",
        "webpack-hot-middleware": "^2.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9304fce836e8a3216b22588f8dc91b447728f0ae",
        "tarball": "https://registry.npmjs.org/react-portal/-/react-portal-3.0.0.tgz"
    },
    "files": [
        "*.md",
        "LICENSE",
        "lib",
        "build"
    ],
    "gitHead": "dee11f89fb180b9bffaa92ca312a033bcc88b254",
    "homepage": "https://github.com/tajo/react-portal#readme",
    "keywords": [
        "react",
        "react-component",
        "modal",
        "lightbox",
        "react-portal",
        "portal",
        "transportation"
    ],
    "license": "MIT",
    "main": "build/portal",
    "maintainers": [
        {
            "name": "miksu"
        }
    ],
    "name": "react-portal",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tajo/react-portal.git"
    },
    "scripts": {
        "build": "mkdir -p build && babel ./lib/portal.js --out-file ./build/portal.js",
        "build:examples": "npm run clean && npm run build:examples:webpack",
        "build:examples:webpack": "cross-env NODE_ENV=production webpack --config webpack.config.prod.babel.js",
        "clean": "rimraf build",
        "lint": "mocha test/eslint_spec.js",
        "prepublish": "cross-env NODE_ENV=production npm run build",
        "start": "node devServerIndex.js",
        "test": "mocha"
    },
    "tags": [
        "react"
    ],
    "version": "3.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
