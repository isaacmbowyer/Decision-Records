# Choosing Layered Archiecture for C# REST API and NEXT.JS Frontend

## Status 
- Accepted

## Context and Problem Statement 
Determining the appropriate archiectural design approach for both the backend (C#) and the frontend (NEXT.JS), proved to be a difficult decision. The goal was to ensure that the code was maintainable, scalable and used seperation of concerns throughout the application. 

## Considered Options
- _Layered Architecture_: Seperating the application into distinct layers (presentation, business and data access)
- _Component-Based Architecture_: System stuctured into self-contained modular units called compoments and each one encapsulates a set of functionaltities.
- _Microservices Architecture_: Decomposed the system into small, independent deployable services.
  
## Decision Outcome 
_Chosen option_: "Layered Architecture" was adopted for both the C# REST API (Backend) and NEXT.JS (Frontend). This is due to the fact that Layered Architecture provides seperation of concerns, making it easier to update and adapt specific components of the system without affecting others. This flexibility makes testing and future deployments much easier to do since each layer is only responsible for a specific task. 

While there are many benefits with Compoment-Based Architecture, for the nature of the system Layered was considered an ideal choice due the complex business logic that would be occuring within multiple components, making dependency management more difficult. 

## Consequences
While Layered Architecture offers many advantages, setting up the initial strucuture of the application required more effort that I orginally thought. It was difficult to understand each compoments within the C4 diagram as I constantly got the layers wrong and had to change the diagram several times. However, once the style was correct - it was easy to understand how each compoment would react to eachother within the code. 

## More information 
- https://bitloops.com/docs/bitloops-language/learning/software-architecture/layered-architecture
- https://medium.com/geekculture/what-is-a-layered-architecture-in-software-design-22152fc06822
