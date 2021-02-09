# Automation Framework for Cypress
This is an Automated test which was build to test **Project**  with Mocha Awesome HTML Reportings.

Page object model is followed, where all tests are present under **cypress/integration** and page objects are in **cypress/support**

## Installation
Use node package manager to install [Cypress](https://docs.cypress.io/guides/getting-started/installing-cypress.html#System-requirements), or direct download [Cypress](https://www.cypress.io/)

![image](https://user-images.githubusercontent.com/78784343/107335607-23bffa00-6ade-11eb-9c64-a61f51f1d87f.png)

![installing-cli](https://user-images.githubusercontent.com/78784343/107340471-d21a6e00-6ae3-11eb-8c22-24995a566928.gif)

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

