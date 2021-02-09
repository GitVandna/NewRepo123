# Automation Framework for Cypress
This is an Automated test which was build to test **Project**  with Mocha Awesome HTML Reportings.

Page object model is followed, where all tests are present under **cypress/integration** and page objects are in **cypress/support**

## Installation
Use node package manager to install [Cypress](https://docs.cypress.io/guides/getting-started/installing-cypress.html#System-requirements), or direct download [Cypress](https://www.cypress.io/)

[!](https://www.dropbox.com/s/3kf4nnierfoyjcj/feedback%20window.png?dl=0)

## Test Execution
1. Clone repo
2. Go to project root directory (where package.json is present)
3. Open cmd/terminal and run command:
```bash
npm test
```
This will automatically start downloading node modules required to run test and will start executing test. Will take some time initially to download node modules.
## Reports
1. Open mochawesome.html in browser to view test report - ./output/mochawesome.html
2. Screenshot and videos under ./cypress folder

### Note
You can change site url in baseUrl parameter from cypress.json

