# Applying Seperation of Concerns in Frontend and Backend

## Status 
- Accepted
  
## Context and Problem Statement 
Since the project is complex, maintaining a scalable and modular codebase becomes important. It is cruical that the code does not become tightly coupled in both the frontend and backend as it would lead to challenges in code readability, maintainability and testing. To address these issues the need to adop a design pattern was crucial.  

## Considered Options
- _Seperation of Concerns_: Structures the codebase in a way that lets each module be responsible for a specific task.
- _Factory Method_: Defines an interface for creating objects, but lets subclasses decide which classes to instantiate.

## Decision Outcome 
_Chosen Option:_ Implement "Seperation of Concerns" pattern in both the frontend and backend codebase. This decision aims to provide a foundation for future scalability so that the code remains loosly coupled in order to be more testable and maintainable.

## Consequences
Seperation of concerns had postive consequences as the codebase will be structured into distinct modules, each independently handling a seperate concern. This modularity enhances the ability to work with isolated features more easily as other unreleated parts of the system are never affected. Futhermore, by adopting this pattern it enhances code readability as it provides a clear code organisation. I can easily locate and understand part the code based on its specific tasks and features. This makes testing more easily as each component can be examined on a smaller chunk.  

## More information 
- https://sourcemaking.com/design_patterns
- https://deviq.com/principles/separation-of-concerns
