# npmdoc-package-json-to-readme

#### api documentation for  [package-json-to-readme (v2.0.0)](https://github.com/zeke/package-json-to-readme#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-package-json-to-readme.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-package-json-to-readme) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-package-json-to-readme.svg)](https://travis-ci.org/npmdoc/node-npmdoc-package-json-to-readme)

#### Generate a README.md from package.json contents

[![NPM](https://nodei.co/npm/package-json-to-readme.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/package-json-to-readme)

- [https://npmdoc.github.io/node-npmdoc-package-json-to-readme/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-package-json-to-readme/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-package-json-to-readme/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-package-json-to-readme/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-package-json-to-readme/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-package-json-to-readme/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Zeke Sikelianos",
        "url": "http://zeke.sikelianos.com/"
    },
    "bin": {
        "package-json-to-readme": "index.js",
        "readme": "index.js"
    },
    "bugs": {
        "url": "https://github.com/zeke/package-json-to-readme/issues"
    },
    "dependencies": {
        "github-url-to-object": "^1.6.0",
        "hogan.js": "^2.0.0",
        "strip-ansi": "^0.2.2",
        "sync-exec": "^0.5.0",
        "yargs": "^3.0.4"
    },
    "description": "Generate a README.md from package.json contents",
    "devDependencies": {
        "mocha": "^2.1.0",
        "nixt": "^0.3.0",
        "standard": "^8.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "607d47be99b91376ff15b9bb8059c5e91ea4108e",
        "tarball": "https://registry.npmjs.org/package-json-to-readme/-/package-json-to-readme-2.0.0.tgz"
    },
    "gitHead": "5c5a962558f5a7682cf92d94a3234e533bc8ae29",
    "homepage": "https://github.com/zeke/package-json-to-readme#readme",
    "keywords": [
        "package.json",
        "readme",
        "generator",
        "markdown",
        "documentation"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "zeke"
        }
    ],
    "name": "package-json-to-readme",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zeke/package-json-to-readme.git"
    },
    "scripts": {
        "test": "mocha && standard"
    },
    "standard": {
        "env": {
            "mocha": true
        },
        "ignore": [
            "test/fixtures"
        ]
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
