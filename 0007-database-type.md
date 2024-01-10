# Choosing MySQL as the Relational Database for the REST API

## Status 
- Accepted

## Context and Problem Statement 
Selecting the appropriate database and type for a REST API is an important decision that would impact the performance, scalability and maintenance of the software system. It is crucial that the correct database is addressed so that data is stored and retrieved efficiently and correctly.

## Considered Options
- _MySQL_: A popular open-source relational database system. Powers many of the most accessed applications, including Facebook, Netflix, Uber and Netflix.
- _MongoDB_: A non-relational database (NoSQL) which provides flexibility in handling unstructured data in JSON-like documents. 

## Decision Outcome 
_Chosen Option_: The decision was to employ a relational database, "MySQL" for the REST API. This choice was heavily made on the structured nature of the data and the relationships highlighted in the ERD. The application has entities like "User" connected with "Gender", "Ethnicity" and "Role", which emphasises the suitability of a relational model. MySQL's schema aligns with the application's requirements as it ensures reliable and efficient management of connected data.

## Consequences
One main consequence was that ACID principles are followed in MySQL. This ensured reliable data consistency and durability, which is crucial for a REST API handling visa operations. Furthermore, MySQL is scalable, it can easily adapt to growing datasets and increased API usage - this is extremely useful for the system as there will be an increased amount of growing users and visa requests. 

## More information 
- https://www.oracle.com/mysql/what-is-mysql/
- https://www.dbvis.com/thetable/a-guide-to-acid-in-mysql/
