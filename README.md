# Redux Store

A store created using the MERN stack, where the React Context API has been removed and the application has been refactored to use Redux.

Original code from Trilogy Education Services.

[Redux Store short demo](./docs/assets/redux-store-demo.gif)

## User Story

AS a senior engineer working on an e-commerce platform
I WANT my platform to use Redux to manage global state instead of the Context API
SO THAT my website's state management is taken out of the React ecosystem

## Acceptance Criteria

GIVEN an e-commerce platform that uses Redux to manage global state
WHEN I review the app’s store
THEN I find that the app uses a Redux store instead of the Context API
WHEN I review the way the React front end accesses the store
THEN I find that the app uses a Redux provider
WHEN I review the way the app determines changes to its global state
THEN I find that the app passes reducers to a Redux store instead of using the Context API
WHEN I review the way the app extracts state data from the store
THEN I find that the app uses Redux instead of the Context API
WHEN I review the way the app dispatches actions
THEN I find that the app uses Redux instead of the Context API

### Requirements:

- [x] Retains all the functionality of the original application.

- [x] Application must be deployed to Heroku.
