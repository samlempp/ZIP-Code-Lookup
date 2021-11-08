---
layout: page
title: Assignment 11  - Test Coverage Report
permalink: /deliverables/assignment11/
---

<h2><a href="https://samlempp.github.io/ZIP-Code-Lookup/deliverables/coverage/backend/index.html">Django Backend Coverage Report</a></h2>

<p>For the backend, we currently are at 75% test coverage. We are using a lot of built-in Django features (i.e. user authentification), so it is not surprising that we already have strong coverage in our code. That being said, more tests need to be written for our original pieces of code to reach full coverage, as we do not have many written at the time being. For example, we have no tests written specifically for the dashboard app in our project- this will be our top priority for testing on the backend going forward. Much of the code does not require testing, as it was provided by Django and thus already has strong coverage and is known to work. Overall, most of our testing will deal with making sure the request system works and will occur predominantly on the front end in regards to making sure components render correctly.</p>

<h2><a href="https://samlempp.github.io/ZIP-Code-Lookup/deliverables/lcov-report/index.html">React Frontend Coverage Report</a></h2>

<p>This test report is for all files of the code that is located within the “frontend” directory inside of our Pear project. The React frontend is being tested with Jest and React Testing Library, which is what is recommended by React. The coverage of the test report is 44.44% of statements, 50% of branches, 26.2% of functions, and 46.15% of lines which represents a test suite that is in between being healthy and unhealthy. This is partly due to our babel-dependency, it is causing two tests to fail due to an issue that has not yet been identified. It appears Jest is having trouble testing through a .png image that is in our images folder within the src directory. In addition to this, our test coverage is not touching all lines of code within three of our react components: Signup.js, AddData.js, and Upload.js. The top testing priorities within the React frontend aspect of our software is to ensure that the components are being exported and rendering, that the events within some of the components are being toggled, and that the data fetching is successfully completed. All these testing priorities are extremely important as they all must work together for our software to function correctly. We have had some issue testing the data fetching from our Django API, however, this will be correctly tested before our software is fully developed.
</p>
