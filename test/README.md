#Running all tests
From the root directory of your project (or where gulpfile.js is located), run:
  `$ gulp dev-unit`

#Front end unit tests
##Running front end tests
Front end tests may be run using:
  `$ gulp dev-karma`

#Configuration
In the **/tests/** folder there is a **karma.conf.js** file, under the **files** section add the path to your front end javascript as well as the path to any javascript libraries you are using (like angular)

##Adding tests
Tests should be put in the **/tests/unit/frontend/** folder in files ending in **.js**

##Libraries used
Front end tests are run using the [karma test runner](http://karma-runner.github.io/)
  Tests are run using [PhantomJS](http://phantomjs.org/), a headless browser.
  The test framework used is [mocha](http://mochajs.org/)
  The assertion library used is [chai](http://chaijs.com/))
  Stubs, spies and mocks are provided by [sinon](http://sinonjs.org/)
  Test coverage is provided by [instanbul](https://gotwarlost.github.io/istanbul/), and the generated html files may be found in the **/coverage/PhantomJS/** folder

##Resources
Getting started unit testing angular
  [slides](https://w3-connections.ibm.com/wikis/home?lang=en-us#!/wiki/W8bc0477e69af_4e94_aa73_52d7665cdbdf/page/Unit%20Testing)
  [document](https://w3-connections.ibm.com/wikis/home?lang=en-us#!/wiki/W8bc0477e69af_4e94_aa73_52d7665cdbdf/page/Front%20End%20Unit%20Testing)


#Back end unit tests
##Running front end tests
Back end tests may be run using:
  `$ gulp dev-backend`

##Adding tests
Back end unit tests should be put in the **/tests/unit/server/** folder in files ending in **.spec.js**

##Libraries used
Front end tests are run using the [karma test runner](http://karma-runner.github.io/)
  The test framework used is [mocha](http://mochajs.org/)
  The assertion library used is [chai](http://chaijs.com/))
  Stubs, spies and mocks are provided by [rewire](https://github.com/jhnns/rewire/)

##Resources
Getting started unit testing node
  [slides](https://w3-connections.ibm.com/wikis/home?lang=en-us#!/wiki/W8bc0477e69af_4e94_aa73_52d7665cdbdf/page/Unit%20Testing)
  [document](https://w3-connections.ibm.com/wikis/home?lang=en-us#!/wiki/W8bc0477e69af_4e94_aa73_52d7665cdbdf/page/Server%20Side%20Unit%20Testing)
