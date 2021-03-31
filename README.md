# cypress-sandbox 🌲

This project allows one to get up and running with Cypress in no time. Fork this project to use it as a starter if you so wish. 

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

You can run tests headlessly via the following code:

```
yarn cypress run
```

Run an individual spec:

```
yarn cypress run -s [path to spec]
```

Run an individual test by adding `only` to the `it` hook:

```
it.only('name', () => { ...
```

Check out documentation further here - https://docs.cypress.io/guides/getting-started/writing-your-first-test

## Practical Learning

To get some practical experience, the following tasks might be useful:

* Try querying elements - https://docs.cypress.io/guides/core-concepts/introduction-to-cypress#Cypress-Can-Be-Simple-Sometimes
*	Try to find a way to use these common assertions - https://docs.cypress.io/guides/references/assertions#Common-Assertions
*	Try to use a few of these actions - https://docs.cypress.io/guides/core-concepts/interacting-with-elements#Actionability
* Try taking screenshots and videos - https://docs.cypress.io/guides/guides/screenshots-and-videos#Screenshots
*	Try using variables and aliases - https://docs.cypress.io/guides/core-concepts/variables-and-aliases

## FAQ

What is this? 

```<reference types="cypress" />```

This is a tripple slash directive. It tells Intellisense what formatting to use.

References
* https://docs.cypress.io/guides/tooling/IDE-integration#Writing-Tests
* https://www.typescriptlang.org/docs/handbook/triple-slash-directives.html
