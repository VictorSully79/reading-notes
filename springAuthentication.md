# Spring Security Architecture
notes take from https://spring.io/guides/topicals/spring-security-architecture/

## Authentication and Access Control
### Two Main Points
 - Who are you?
 - What are you allowed to do?

### Authentication

### There is only one method in Spring

### `AuthenticationManager` does 3 things:
- Return an `Authentication` (normally with `authenticated=true`) if it can verify that the input represents a valid principal.
- Throw an `AuthenticationException` if it believes that the input represents an invalid principal.
- Return `null` if it cannot decide.
  
