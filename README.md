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
node_modules/google-closure-compiler/contrib/nodejs/path.js:97: WARNING - name module is not defined in the externs.
module.exports = path;
^^^^^^

node_modules/google-closure-compiler/contrib/nodejs/path.js:97: ERROR - variable module is undeclared
module.exports = path;
^^^^^^

1 error(s), 1 warning(s)
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```
