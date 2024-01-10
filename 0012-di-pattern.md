# Applying Dependency Injection (DI) pattern for Backend REST API

## Status 
- Accepted
  
## Context and Problem Statement 
As the REST API is developed, it is important that the dependencies within the codebase are managed. The need to inject repositories and DbContexts within each controller to ensure proper data access and management was crucial for code maintainability, testability and scalability.

## Considered Options
- _Dependency Injection (DI)_: Programming pattern technique in which an function or object receives other objects or functions that it requires.
- _Strategy Pattern_: Defines multiple algorithms and encapsulates each one. The client at runtime will choose an algorithm and enable the selection of different strategies without altering the code.

## Decision Outcome 
_Chosen Option_: "Dependency Injection (DI)" will be used for the Backend REST API, specifically to inject repositories and DbContexts within each controller. 

## Consequences
The decision to use Dependency Injection (DI) emphasizes decoupling as it ensures loose connections between controllers and components for a modular and maintainable codebase. Despite a potential learning curve, the long-term benefits, such as an  improved code organisation outweigh the disadvantage.

## More information 
- https://sourcemaking.com/design_patterns/strategy
- https://learn.microsoft.com/en-us/dotnet/core/extensions/dependency-injection
