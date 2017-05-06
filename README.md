closure-node-sample1
====

## How to build

```console
$ git clone git@github.com:teppeis-sandbox/closure-node-sample1.git
$ cd closure-node-sample1
$ yarn
$ yarn run build
yarn run v0.23.3
$ closure-compiler --flagfile closure.conf 
index.js:1: WARNING - Failed to load module "path"
var path = require('path');
    ^

index.js:1: WARNING - Failed to load module "path"
var path = require('path');
           ^

index.js:1: ERROR - Variable path first declared in node_modules/google-closure-compiler/contrib/nodejs/path.js
var path = require('path');
    ^^^^^^^^^^^^^^^^^^^^^^

1 error(s), 2 warning(s)
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```
