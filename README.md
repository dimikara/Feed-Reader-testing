# Feed Reader Project - Overview

In this project we were given a web-based application that reads RSS feeds. The application included [Jasmine](http://jasmine.github.io/) and had the first test suite written. The objective of the project was to complete the rest of the tests and understand the underlying business logic of the application, as well as the event handling and DOM manipulation.
___


# Description of Tests

* A test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
* A test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
* Creation of a test suite named `"The menu"`. This test suite contains a test ensuring that the menu element is hidden by default and a test ensuring that the menu changes visibility when the menu icon is clicked. This latter test has two expectations: the menu displays when clicked and it hides when clicked again.
* Creation of a test suite named `"Initial Entries"`. This test suite contains a test ensuring that when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container. Since `loadFeed` function is asynchronous, this test requires the use of Jasmine's `beforeEach` and asynchronous `done` function.
* Creation of a test suite named `"New Feed Selection"`. This test suite contains a test ensuring that when a new feed is loaded by the `loadFeed` function that the content actually changes.

* **NOTE**: No test is dependent on the results of another.
___


# How to execute the application

* Simply run the index.html file in the project folder.
The tests are included in the file /jasmine/spec/feedreader.js.

* If you see the green part in the bottom of the page, it means that the application was successful and all the checks passed.

![Screenshot1](/img/Check_pass.png "Check_pass")

* If one or more checks failed, Jasmine flags them with red and gives the relevant details.

![Screenshot2](/img/Check_failed.png "Check failed")

___


# Tools & Resources used

* **HTML**, **CSS**, & **Javascript**.
* **[Jasmine](http://jasmine.github.io/)**. It is an open source, behavior-driven development framework for testing JavaScript code. The version used here is 2.1.2. while the latest release (as of 06/2018) is 3.1.0.
___


# Credits

**Mohammed Riaad**'s presentation during the 2nd Study Jam was very helpful to surpass the points where I had stuck.
___
