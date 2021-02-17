automation-practice-bdd-wdio
====================

Project to run WebdriverIO tests with [Cucumber](https://cucumber.io/) and brings **true** [BDD](http://en.wikipedia.org/wiki/Behavior-driven_development) to JavaScript. Instead of writing complicated test code that only developers can understand, Cucumber maps an ordinary language to code and allows to start with the test process in the early stages of your product development.

## Requirements

- Node version 10 or higher


Although this project works fine with NPM 

## Quick start

Choose one of the following options:

1. Download the latest stable releaseo r clone the git repo

2. Clean the project (Optional):


3. Install the dependencies 
  -- npm intall

4. To run your tests just call the [WDIO runner](http://webdriver.io/guide/testrunner/gettingstarted.html):

```bash
$ node run testrun
```
5. To generate the allure report 


```bash
$ node run allure-report-generate
```
5. To open report by starting allure server 

```bash
$ node run allure-report-open
```
# Features (scenarios) tested:

Feature: Register,login and check-out the product

  Scenario: As a user, I can open automation webpage 

    Given I am on the automation practice webpage
    When I should see and click on the Sign button
    Then I can create account by entering emailid
    Then Enter personal information and should click on Register button
    Then Validate Landing page
    Then Add product to cart and Proceed to checkout
    Then Validate the product on Payment page 


# Running single feature
Sometimes it's useful to only execute a single feature file, to do so use the following command:



