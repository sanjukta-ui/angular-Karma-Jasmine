Angular Testing Techniques
==========================

This is a simple example to demonstrate various techniques to test Angular apps, specifically:

1. Visualizing different states of a component using Storybook
2. Unit testing a component
3. Integration testing the entire app
4. Visual regression testing the entire app

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.8.

Quick Start
-----------
$ npm install 
$ ng serve

Now point your browser to http://localhost:4200/.

Visualize component states
--------------------------
Allows you to visualize different states of your UI components and develop them interactively.

#### Tools
- [Storybook](https://storybook.js.org/)

#### Tests
- [index.stories.ts](src/stories/index.stories.ts): Instantiates the `OrderViewComponent` in five different states to ensure that it is rendered correctly.

#### Running the tests

    yarn storybook
    
Point your browser to http://localhost:6006/


Unit testing
------------
Tests a single component in isolation.

#### Running the tests

    ng test


Integration (end-to-end) testing
--------------------------------
Tests an entire app with multiple components, pages and navigation, while fully integrated with its back-end.

#### Running the tests

    ng e2e

Screenshot (visual regression) testing
--------------------------------------
#### Running the tests

    npm screenshot-test
