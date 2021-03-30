# cypress-sandbox 🌲

## Prerequisites 
* Node.js - https://nodejs.org/en/download/
* Git - https://git-scm.com/downloads

## Installing and Running Cypress
First, clone this repo 
```
git clone https://github.com/thefungiz/cypress-sandbox.git
```
Next, install dependencies and open cypress
```
cd ./cypress-sandbox
npm install --global yarn
yarn install
yarn cypress open // might fail the first time while cypress is being 'verified' by the OS. Just run again.
```
Then test out some of the examples and have some fun

Check out documentation further here - https://docs.cypress.io/guides/getting-started/writing-your-first-test

## FAQ

What is this? 
```<reference types="cypress" />```
This is a tripple slash directive. It tells Intellisense what formatting to use.
References
* https://docs.cypress.io/guides/tooling/IDE-integration#Writing-Tests
* https://www.typescriptlang.org/docs/handbook/triple-slash-directives.html
