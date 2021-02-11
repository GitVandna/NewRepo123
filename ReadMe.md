# Cypress-Cucumber-Framework

The *Cypress-Cucumber-Preprocessor* add support for using features files when testing with cypress.

## Installation

Install the plugin by running:

`npm install --save-dev cypress-cucumber-preprocessor`

## Cypress Configuration
Add it to your plugins:

cypress/plugins/index.js

## Organizing the tests

Put your feature files in cypress/integration/
Example: cypress/integration/

## Test Execution

`cypress run --spec **/*.features`

## How to write test

We use [Cucumber Expression](https://cucumber.io/docs/cucumber/cucumber-expressions/) to parse your .feature file.

## Given/When/Then Functions

## How to run tests
Use command in your terminal
`./node_modules/.bin/cypress open`

Click on .feature file on the list of specs. And execution starts

## Run tagged tests

You can use tags to select which test should execute using [cucumber's tag expressions](https://github.com/cucumber/cucumber/tree/master/tag-expressions).

## Ignoring Specific scenarios using tags

You can also use tags to ignore specific scenarios when running cypress test runner

You can add "env" property with the "TAGS" in cypress.json configuration file.
```
{
    "env": {
        "TAGS": "not @ignore"
    },
    //rest of configuration options
    "baseUrl": "yourBaseUrl",
    "ignoreTestFiles": "*.js",
    //etc
}
```
