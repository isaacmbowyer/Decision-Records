# Utilizing Security with Salt and JWT Authentication

## Status 
- Accepted

## Context and Problem Statement 
It is crucial to ensure that security measures within the system are developed to safeguard sensitive user information and authenticate users securely. The challenge to select appropriate security tools for password storage and user authentication was raised. 

## Considered Options
- Hashing with Salt: Utilizing a combination of hashing with salt for secure password storage
- Hashing without Salt: Implementing hashing without the addition of salt for password storage
- JSON Web Token (JWT) Authentication: Used for authentication and authorization

## Decision Outcome 
_Chosen Options_: Given the requirements, the chosen approaches were to employ "Hashing with Salt" for password storage and "JWT Authentication" for authorization to services when user interacts with the REST API.   

## Consequences
By implementing a combination of hashing with a unique salt, the system is protected against potential cyber threats as it adds an extra layer of complexity, making it more challenging for attackers to decipher passwords, even if they gain access to the hashed values. Furthermore, the use of JWT authentication ensures that users can only access resources for which they have explicit authorization, reinforcing the overall security of the API, as it eliminates the need for a server-side session management.

## More information 
- https://jwt.io
- https://en.wikipedia.org/wiki/Salt_(cryptography)
