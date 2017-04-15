# test coverage for  [traceur (v0.0.111)](https://github.com/google/traceur-compiler)  [![npm package](https://img.shields.io/npm/v/npmtest-traceur.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-traceur) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-traceur.svg)](https://travis-ci.org/npmtest/node-npmtest-traceur)
#### ES6 to ES5 compiler

[![NPM](https://nodei.co/npm/traceur.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/traceur)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-traceur/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-traceur/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-traceur/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-traceur/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-traceur/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-traceur/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-traceur/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-traceur/build/screenCapture.buildCi.browser.coverage.example.html.png)](https://npmtest.github.io/node-npmtest-traceur/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-traceur/build/screenCapture.buildCi.browser.test-report.html.png)](https://npmtest.github.io/node-npmtest-traceur/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-traceur/build/screenCapture.buildCi.browser.apidoc.html.png)](https://npmdoc.github.io/node-npmdoc-traceur/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-traceur/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-traceur/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Traceur Authors"
    },
    "bin": {
        "traceur": "./traceur"
    },
    "bugs": {
        "url": "https://github.com/google/traceur-compiler/issues"
    },
    "contributors": [
        {
            "name": "The Chromium Authors"
        },
        {
            "name": "Google Inc."
        },
        {
            "name": "Viktor Kronvall"
        },
        {
            "name": "Ben Chan"
        },
        {
            "name": "Eduard Burtescu"
        },
        {
            "name": "Peter Hallam"
        },
        {
            "name": "Nick Schonning"
        },
        {
            "name": "Kinya TERASAKA"
        },
        {
            "name": "Sean Middleditch"
        },
        {
            "name": "Ross Hadden"
        },
        {
            "name": "Stephan Seidt"
        },
        {
            "name": "Mathias Bynens"
        },
        {
            "name": "Tommy Odom"
        },
        {
            "name": "Rolf Timmermans"
        },
        {
            "name": "Tomi Belan"
        },
        {
            "name": "James Lal"
        },
        {
            "name": "Galimzyanov Dmitry"
        },
        {
            "name": "Rick Waldron"
        },
        {
            "name": "A. Matías Quezada"
        },
        {
            "name": "Sam Day"
        },
        {
            "name": "Guy Bedford"
        },
        {
            "name": "Jeff McRiffey"
        },
        {
            "name": "Marius Nita"
        },
        {
            "name": "Nick Fitzgerald"
        },
        {
            "name": "Gil Tayar"
        },
        {
            "name": "Aleksander Heintz"
        },
        {
            "name": "Ulrik de Muelenaere"
        },
        {
            "name": "Maël Nison"
        },
        {
            "name": "Shinnosuke Watanabe"
        },
        {
            "name": "Vyacheslav Shebanov"
        },
        {
            "name": "Fabrício Matté"
        },
        {
            "name": "Jordan Harband"
        },
        {
            "name": "Martín Ciparelli"
        },
        {
            "name": "David Håsäther"
        },
        {
            "name": "Amjad Masad"
        },
        {
            "name": "Peter Flannery"
        },
        {
            "name": "Liubomyr Mykhalchenko"
        },
        {
            "name": "Dmitry Soshnikov"
        },
        {
            "name": "Victor Berchet"
        },
        {
            "name": "Paul Selden"
        },
        {
            "name": "Steven Vachon"
        },
        {
            "name": "Maga D. Zandaqo"
        },
        {
            "name": "Valeriy Sorokobatko"
        },
        {
            "name": "Ivan Willig"
        },
        {
            "name": "Oliver Joseph Ash"
        },
        {
            "name": "Chris Truter"
        },
        {
            "name": "Marc Nieper-Wißkirchen"
        },
        {
            "name": "Rogério Yokomizo"
        },
        {
            "name": "Caitlin Potter"
        },
        {
            "name": "Srinivasan Sekar"
        },
        {
            "name": "Jeff Shen"
        },
        {
            "name": "Erik Arvidsson"
        }
    ],
    "dependencies": {
        "commander": "2.9.x",
        "glob": "5.0.x",
        "rsvp": "^3.0.13",
        "semver": "^4.3.3",
        "source-map-support": "~0.2.8"
    },
    "description": "ES6 to ES5 compiler",
    "devDependencies": {
        "chai": "2.2.x",
        "express": "4.x",
        "mocha": "2.2.x",
        "node-uuid": "1.x",
        "promises-aplus-tests": "2.x",
        "regenerate": "1.2.1",
        "regexpu": "1.1.0",
        "regjsgen": "0.2.0",
        "regjsparser": "0.1.5",
        "requirejs": "2.x",
        "serve-index": "1.x",
        "source-map": "0.1.43",
        "traceur": "0.0.110",
        "webcomponents.js": "^0.5.4-1"
    },
    "directories": {},
    "dist": {
        "shasum": "c04de74d14696c3373427de4fc08ecaf913fc3a1",
        "tarball": "https://registry.npmjs.org/traceur/-/traceur-0.0.111.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "files": [
        "bin/traceur.js",
        "bin/traceur.js.map",
        "bin/traceur-runtime.js",
        "bin/BrowserSystem.js",
        "src/",
        "dist/",
        "traceur"
    ],
    "gitHead": "2ddade7061e895b7dddb56ed4b89df310386860b",
    "homepage": "https://github.com/google/traceur-compiler",
    "keywords": [
        "javascript",
        "ecmascript",
        "language",
        "es5",
        "es6",
        "ES.next",
        "harmony",
        "compiler",
        "transpiler"
    ],
    "license": "Apache-2.0",
    "main": "./src/node/api.js",
    "maintainers": [
        {
            "name": "arv"
        },
        {
            "name": "johnjbarton"
        }
    ],
    "name": "traceur",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/google/traceur-compiler.git"
    },
    "scripts": {
        "/** Update Version Number **/": "After publishing version N, update the version number and commit the result",
        "/** Update gh-pages branch **/": "Ater publishing version N, update the github docs and REPL",
        "checkout-gh-pages": "git checkout -b upstream_gh_pages upstream/master",
        "checkout-upstream": "git checkout -b upstream_master upstream/master",
        "commit-gh-pages": "git add -- src/ bin/ && ./traceur -v | xargs -I VERSION git commit -a -m \"Commit binaries for VERSION\"",
        "commit-published": "cat build/npm-version-number | xargs -I VERSION git commit -a -m \"VERSION\"",
        "just-publish": "npm publish # workaround https://github.com/npm/npm/issues/10074 ",
        "postjust-publish": "npm run push-published && npm run push-gh-pages",
        "postpush-gh-pages": "git checkout master && git branch -D upstream_gh_pages",
        "postpush-published": "git checkout master && git branch -D upstream_master",
        "precheckout-gh-pages": "git branch -D upstream_gh_pages || true",
        "precheckout-upstream": "git fetch upstream && git branch -D upstream_master || true",
        "precommit-gh-pages": "npm run checkout-gh-pages && npm run rebuild && cp gh-pages.gitignore .gitignore # tell git to commit built files.",
        "precommit-published": "npm run update-semver && npm run rebuild",
        "prejust-publish": "npm run checkout-upstream && npm run rebuild",
        "prepush-gh-pages": "npm run commit-gh-pages",
        "prepush-published": "npm run commit-published && npm run tag-published",
        "push-gh-pages": "git push -f upstream upstream_gh_pages:gh-pages",
        "push-published": "git push --tags upstream upstream_master:master && git push upstream upstream_master:master  # Push source for version N+1",
        "rebuild": "make clean && make dist/commonjs && make test",
        "start": "make && node ./demo/expressServer.js",
        "store-semver": "node build/versionInfo.js -v > build/npm-version-number",
        "tag-published": "cat build/npm-version-number | xargs -I VERSION git tag -a VERSION -m \"Tagged version VERSION \"",
        "test": "make test",
        "update-semver": "npm run store-semver && git diff --quiet -- package.json && node build/versionInfo.js -n"
    },
    "subdomain": "traceur",
    "version": "0.0.111"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
