# Using MADR for Decisions Records

## Status 
- Accepted

## Context and Problem Statement 
There was increased challenges of selecting an appropriate format for documenting the architectural decisions that occurred  during the software development process within the application. It was important to select an approach that was simple and informative. 

## Considered Options
It was decided that Markdown Architectural Decision Records (MADR) would be used as:
- Lightweight decision records
- MADR decision records
- Plain text documents
  
## Decision Outcome 
_Chosen option_: "MADR" emerged as the ideal choice for our architectural decision documentation. This is due to MADR's structured and standardized approach as it has predefined template for recording architectural decisions and their consequences, which stood as a clear advantage. This contrasts with lightweight and plain text documents as it lacks a consistent template, which would lead to challenges in maintaining consistency - making it harder to digest the information.

## Consequences
The standard template provided by MADR enhanced the ease of reference within the decision records. With the structured approach, I found that I could quickly locate the relevant information and it acted as a reminder for the reason behind each architectural decision. However, the format did pose a learning curve as it was difficult to become familiar with the template and took multiple iterations to get the standard right. 

## More information 
- https://adr.github.io/madr/
