# WebdriverIO Documentation

## Setup Requirement

- Install at least node v16.x or v18.x, using 'nvm install 18' or `brew install node@18` should work.
- To manually set node version to 18 use 'nvm use 18'.
- Check system chrome browser version compatible with chromedriver.

## Setting Up repository

- git clone git@github.com:sanjitroy1992/WebdriverIO_Automation.git
- git pull
- git checkout -b <your own branch>
- Install all npm packages at root level with `npm install`
- .env file contains all variables needed

## Running Tests

- In package.json, under script "tests" update the tag name in --cucumberOpts.tags='@<tag_name>'"
- Example: --cucumberOpts.tags='@login'
- To run tests, use `npm run tests`

## Test Result

- To view allure report do "npm run report" post execution completed
