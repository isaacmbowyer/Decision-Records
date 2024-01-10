# Choosing Jest for Frontend Testing 

## Status 
- Accepted

## Context and Problem Statement 
When selecting a testing framework for the frontend development of the application, the goal was to ensure overall test coverage for the components, util functions and services. The challenge was to identify a testing tool that aligns with the project's needs, easy to configure and provides modern day testing scenarios. 

## Considered Options
- _Jest_: A popular testing framework that includes an assertion library and mocking capabilities. 
- _Cypress_: An end-to-end framework that enables testing applications in a real browser. 
- _Sinon_: A library for creating mocks, spies and stubs.
  
## Decision Outcome 
_Chosen Option:_ "Jest" testing framework was adopted due to its extensive documentation and integration with tools like React and TypeScript made it well-suited for testing utils, components and services. 

## Consequences
The decision to use Jest as a testing framework was influenced by its time-saving advantages and default configuration setup. This will reduce the initial setup time, allowing for a swift start in coding tasks. Additionally, the built-in mocking functionalities of Jest will enhance the testing process, especially with its capabilities of mocking return types of services. This will prove valuable when validating API interactions during deployment preparations.

## More information 
- https://jestjs.io/docs/getting-started
-
