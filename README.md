# JS Testing Framework

* A simple testing framework for Javascript, modeled after Jasmine. Created for Makers Academy.

## How to Use

* Copy `tester.js` into your project directory.
* Write unit tests in spec files as you would in Jasmine, with `describe`, `it` and `beforeEach` blocks.
  - currently available matchers are `toBe`, which tests for strict equality of two expressions, and `toInclude`, which tests for inclusion of an element within a collection.
* Add a `spec_runner.html` file that loads `tester.js`, your unit test files, and your model code.
* Open `spec_runner.html` in a browser and open the console to see the outcome of your tests. 
