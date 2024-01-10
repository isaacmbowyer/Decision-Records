# Utilizing Security with Salt and JWT Authentication

## Status 
- Accepted

## Context and Problem Statement 
It is cruical to ensure that security measures within the system are developed to safegaurd sensitive user information and authenticate users securely. The challange to select appropriate security tools for password storage and user authentication was raised. 

## Considered Options
- Hashing with Salt: Utilizing a combination of hashing with salt for secure password storage
- Hashing without Salt: Implementing hashing without the addition of salt for password storage
- JWT Authentication: Used for authentication and authorization

## Decision Outcome 
_Chosen Options_: Given the requirements, the chosen approaches were to employ "Hashing with Salt" for password storage and "JWT Authentication" for authroization to services when user interacts with the REST API.   

## Consequences


## More information 
- https://jwt.io
- https://en.wikipedia.org/wiki/Salt_(cryptography)
