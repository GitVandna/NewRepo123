# Automation Framework for Cypress
This is an Automated test which was build to test **Project**  with Mocha Awesome HTML Reportings.

Page object model is followed, where all tests are present under **cypress/integration** and page objects are in **cypress/support**

## Installation
A step by step series of examples that tell you how to get a development env running.
Use node package manager to install [Cypress](https://docs.cypress.io/guides/getting-started/installing-cypress.html#System-requirements), or direct download [Cypress](https://www.cypress.io/)

![installing-cli](https://user-images.githubusercontent.com/78784343/107340471-d21a6e00-6ae3-11eb-8c22-24995a566928.gif)

## Test Execution terminal
1. This command will execute all avaliable tests:

npm run test:e2e

## Test Execution through UI
This command will open Cypress GUI:

npm run cypress open

![image](https://user-images.githubusercontent.com/78784343/107335607-23bffa00-6ade-11eb-9c64-a61f51f1d87f.png)

## Example

Code below will take you to google.com
cy.visit("https://www.google.com/")

In cypress this is how you can click on a button using its locator
cy.get('.gLFyf.gsfi').click();

To type in a text box
  cy.get('.gLFyf.gsfi').type('cyress tutorials');

To wait for an element to appears on page
cy.wait(5000) //

## Reports
1. Open mochawesome.html in browser to view test report - ./output/mochawesome.html
2. Screenshot and videos under ./cypress folder

### Note
You can change site url in baseUrl parameter from cypress.json

