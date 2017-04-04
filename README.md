# api documentation for  [karma-mocha (v1.3.0)](https://github.com/karma-runner/karma-mocha#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-karma-mocha.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-karma-mocha) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-karma-mocha.svg)](https://travis-ci.org/npmdoc/node-npmdoc-karma-mocha)
#### A Karma plugin. Adapter for Mocha testing framework.

[![NPM](https://nodei.co/npm/karma-mocha.png?downloads=true)](https://www.npmjs.com/package/karma-mocha)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-mocha/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-karma-mocha_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-mocha/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-karma-mocha/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-karma-mocha/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vojta Jina",
        "email": "vojta.jina@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/karma-runner/karma-mocha/issues"
    },
    "contributors": [
        {
            "name": "Maksim Ryzhikov",
            "email": "rv.maksim@gmail.com"
        },
        {
            "name": "Friedel Ziegelmayer",
            "email": "friedel.ziegelmayer@gmail.com"
        },
        {
            "name": "dignifiedquire",
            "email": "friedel.ziegelmayer@gmail.com"
        },
        {
            "name": "Jordan Klassen",
            "email": "jordan@vidigami.com"
        },
        {
            "name": "Martin Hansen",
            "email": "martin@martinhansen.no"
        },
        {
            "name": "Mark Ethan Trostler",
            "email": "mark@zzo.com"
        },
        {
            "name": "Dave Geddes",
            "email": "davidcgeddes@gmail.com"
        },
        {
            "name": "Aliaksei Shytkin",
            "email": "e79eas@gmail.com"
        },
        {
            "name": "Pawel Kozlowski",
            "email": "pkozlowski.opensource@gmail.com"
        },
        {
            "name": "Christopher Hiller",
            "email": "boneskull@boneskull.com"
        },
        {
            "name": "Lukasz Bandzarewicz",
            "email": "lucassus@gmail.com"
        },
        {
            "name": "Jonathan Knapp",
            "email": "jon@coffeeandcode.com"
        },
        {
            "name": "Karolis Narkevicius",
            "email": "karolis.n@gmail.com"
        },
        {
            "name": "Mark Trostler",
            "email": "mark@zzo.com"
        },
        {
            "name": "Peter Halliday",
            "email": "pghalliday@gmail.com"
        },
        {
            "name": "Raphael Luba",
            "email": "raphael@leanbyte.com"
        },
        {
            "name": "Sahat Yalkabov",
            "email": "sakhat@gmail.com"
        },
        {
            "name": "Tim Macfarlane",
            "email": "timmacfarlane@gmail.com"
        },
        {
            "name": "Vova Bilonenko",
            "email": "bilonenko.v@gmail.com"
        },
        {
            "name": "dej611",
            "email": "marco@terraling.com"
        },
        {
            "name": "eiriksm",
            "email": "eirik@morland.no"
        },
        {
            "name": "patrick kettner",
            "email": "patrickkettner@gmail.com"
        },
        {
            "name": "Aymeric Beaumet",
            "email": "aymeric@beaumet.me"
        },
        {
            "name": "Christian Schlensker",
            "email": "christian@cswebartisan.com"
        },
        {
            "name": "Christian Schulze",
            "email": "christian.schulze@mywave.me"
        },
        {
            "name": "Ciro S. Costa",
            "email": "ciro.costa@usp.br"
        },
        {
            "name": "Dan Thareja",
            "email": "danthareja@gmail.com"
        },
        {
            "name": "Darryl Pogue",
            "email": "darryl@dpogue.ca"
        },
        {
            "name": "Darryl Pogue",
            "email": "dvpdiner2@gmail.com"
        },
        {
            "name": "JONATHAN PARK",
            "email": "jonathan@silvenstudios.com"
        },
        {
            "name": "James Morris",
            "email": "jamie@maloric.com"
        },
        {
            "name": "Jason Divock",
            "email": "jdivock@gmail.com"
        },
        {
            "name": "Jeff Jagoda",
            "email": "jeffrey.jagoda@gmail.com"
        }
    ],
    "dependencies": {
        "minimist": "1.2.0"
    },
    "description": "A Karma plugin. Adapter for Mocha testing framework.",
    "devDependencies": {
        "chai": "^3.4.1",
        "eslint": "^2.0.0",
        "eslint-config-standard": "^5.1.0",
        "eslint-plugin-promise": "^1.0.8",
        "eslint-plugin-react": "^5.2.2",
        "eslint-plugin-standard": "^1.3.2",
        "grunt": "~1.0",
        "grunt-auto-release": "~0.0.2",
        "grunt-bump": "~0.8.0",
        "grunt-conventional-changelog": "^6.0.1",
        "grunt-eslint": "^18.0.0",
        "grunt-karma": "2.x",
        "grunt-npm": "~0.0.2",
        "karma": "^1.0.0",
        "karma-chai": "^0.1.0",
        "karma-chrome-launcher": "^1.0.0",
        "karma-firefox-launcher": "^1.0.0",
        "karma-sinon": "^1.0.3",
        "load-grunt-tasks": "^3.2.0",
        "mocha": "^3.0.0",
        "mock-fs": "^3.12.1",
        "shared-karma-files": "git://github.com/karma-runner/shared-karma-files.git#82ae8d02",
        "sinon": "^1.17.2"
    },
    "directories": {},
    "dist": {
        "shasum": "eeaac7ffc0e201eb63c467440d2b69c7cf3778bf",
        "tarball": "https://registry.npmjs.org/karma-mocha/-/karma-mocha-1.3.0.tgz"
    },
    "gitHead": "e39c3232d0f6aa8395aedda1ad4a109cb3150db1",
    "homepage": "https://github.com/karma-runner/karma-mocha#readme",
    "keywords": [
        "karma-plugin",
        "karma-adapter",
        "mocha"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "vojtajina",
            "email": "vojta.jina+npm@gmail.com"
        },
        {
            "name": "maksimr",
            "email": "rv.maksim@gmail.com"
        },
        {
            "name": "zzo",
            "email": "mark@zzo.com"
        },
        {
            "name": "dignifiedquire",
            "email": "dignifiedquire@gmail.com"
        },
        {
            "name": "karmarunnerbot",
            "email": "karmarunnerbot@gmail.com"
        }
    ],
    "name": "karma-mocha",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/karma-runner/karma-mocha.git"
    },
    "scripts": {
        "test": "grunt test",
        "test:lib": "mocha test/lib"
    },
    "sharedKarmaFiles": {
        "editorconfig": ".editorconfig",
        "gitattributes": ".gitattributes"
    },
    "version": "1.3.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module karma-mocha](#apidoc.module.karma-mocha)



# <a name="apidoc.module.karma-mocha"></a>[module karma-mocha](#apidoc.module.karma-mocha)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
