# Introduction

This is a sample node for nodered with test

## Add a test

Inside test directory create a file `_spec.js` and make sure that inside `package.json` this entry is present `"scripts": {"test": "mocha \"test/**/*_spec.js\""}`

Also make sure that below are added as dependencies required for tests to run `npm install mocha chai should node-red node-red-node-test-helper --save-dev`

### Running the test

In root directory; `npm test`

## Deploy 

git clone https://github.com/raohammad/noderes-samplenode.git

Inside node-red cloned directory; `npm install /<path-to>/noderes-samplenode`