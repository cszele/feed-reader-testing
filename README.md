# Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development." This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!


## What will I learn?

You will learn how to use Jasmine to write a number of tests against a pre-existing application. These will test the underlying business logic of the application as well as the event handling and DOM manipulation.


## How will this help my career?

Writing effective tests requires analyzing multiple aspects of an application including the HTML, CSS and JavaScript - an extremely important skill when changing teams or joining a new company.

Good tests give you the ability to quickly analyze whether new code breaks an existing feature within your codebase, without having to manually test all of the functionality.

# Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

Udacity Feed reader app testing with Jasmine
Table of Contents
Project Overview
Running the Application
Contributing
Development Strategy
Dependencies
Project Overview
This project demonstrates test-driven javascript using Jasmine on a web-based RSS feeds reader application.

Running the Application
In order to be able to run the application and view the test results, you have to save the folder locally to your computer and then open the index.html file in a browser.

(Jasmine should automatically execute the test suites and the results should be shown at the bottom of the page; all the tests should pass.)

Contributing
In order to access/alter/develop the test suite, navigate to jasmine/spec/feedreader.js and open with the text editor of your choice.

Development Strategy

* Open up `index.html` and review the functionality of the application within your browser
* What is all the code in `app.js` doing? Be sure to read all code comments
* Check out `style.css`. How is styling applied to the application?
Explore the Jasmine spec file in feedreader.js
This is the file in which you'll be writing your tests
Make sure to read all code comments here as well
Review the Jasmine documentation if needed
Edit the allFeeds variable in app.js to make the provided test fail
See how Jasmine visualizes this failure in your application
Return the allFeeds variable to a passing state after reviewing the failed test
Write a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty
For example, how would you use a for...of loop in this test?
Write a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty
Think about how you wrote the previous test. What are you testing for this time?
Write a new test suite named "The menu"
What are you describe-ing in this test suite?
Write a test that ensures the menu element is hidden by default
You'll have to analyze the HTML and the CSS to determine how the hiding/showing of the menu element is implemented
What code in app.js is directly involved with toggling the menu on and off?
Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display itself when clicked, and does it hide when clicked again?
Think about how you wrote the previous test. What is different this time around?
Which clickable element are you checking for?
How do you "simulate" a mouse click that element without actually clicking it?
Write a test suite named "Initial Entries"
What are you describe-ing in this test suite?
Write a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container
How does Jasmine's beforeEach()function work?
How does the loadFeed() function in app.js work? Is it synchronous or asynchronous?
Write a test suite named "New Feed Selection"
What are you describe-ing in this test suite?
Write a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes
How is this test different from the previous test?
Additionally, note that:

No test should be dependent on the results of another
Callbacks should be used to ensure that feeds are loaded before they are tested
Error handling should be implemented for undefined variables and out-of-bound array access
When complete, all of your tests should pass
Dependencies
JQuery

Jasmine
