# Project Feedreader

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.


## RSS Feeds Test Suite

This test suite assures RSS feeds are defined. It consists three test, fisrt test ensures the array that contains the names and url of the feeds it is defined and it is not empty. The second one is to ensure the urls are defined and not empty as well. The third one ensures the feeds objects have name defined and that they are not empty.

## Menu Test Suite

This test suite is about menu functionality, its first test consists of the menu by default being hidden when the program is launched and for the second test when the menu icon is clicked once the menu will appear and when the icon is clicked for the second time the menu will be hidden.


## Initial Entries Test Suite

For this test suite the feed content change when a new feed is loaded, when function loads initial feed it has to wait until this load will finish before it starts a second feed.


## Running test

Using a webbrowser open index.html file, at the bottom of the page a jasmine section will be displayed, click each test name and it will run that test.


