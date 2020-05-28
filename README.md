# QEtestRealPage
Inside this repo "QEtestRealPage",
several folders and files can be used for testing in automated way
the site http://automationpractice.com/

For this solution several dependencies will be needed:
"chai",
"chromedriver",
"selenium-webdriver",
"cucumber"

All them will be installed using NPM.

The test will consider the next cases:

"
Given the following user stories

Feature: User Creates an account

Scenario: User can create an account
Scenario: user can log in account
"

***
Before doing the setup, validates that you already have installed NodeJS (6 or high). 

Also validates that chrome browser from Google is installed.

***
Setup
* Validate the file "package.json"

* Validate the folders "features"/"step_definitions"

* Validate the file "automationpractice.feature" is inside the folder "features"

* Validate the file "automationpractice.js" is inside the folder "step_definitions"

After you have validated this structure, 
open a command console and go to the "QEtestRealPage" directory 
with the "package.json" file inside.


****
Then run the command:

 **npm install**

This will create all the project structure for the "node_modules" folder 
and will create a package-lock.json file.


****
Finally run the command:

**npm test**

This will make a new chrome browser window to appear 
and run the 2 scenarios for the test.
