
# Cypress Automation Demo

This is an example project using the automation tool, Cypress. These tests are quite simple but are intended to provide examples of common actions we may need in testing automation practice.

A Demo application we are going to automate end to end by using CYPRESS as an automation tool. This includes the BDD framework with Cucumber as a plugin where we can write our tests in a very simple language so that technical as well as non technical person can also able to understand the scripts.
Again to optimize the code we are going to create Page objects for the web elements which will ease the way of writing and modifying the scripts.

The Demo included:

* Feature file

* Step Definition file

* page objects

* HTML Report

* various ways of running the tests (via npm scripts)

## Requires:

* Node

* Git
## Deployment

To deploy this project run

1. Clone:https://github.com/rudeshk45/Cypress-Auto.git

2. ```bash 
      npm install 
      ```




## Run the Tests

1. All Tests   :  
```bash  
npm test
```


2. Just homePage  : 
```bash 
npm run cy:homePage
```
3. Headless       : 
```bash
npm run cy:headless
```