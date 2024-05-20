# Spring-JWT-Authentication-and-Authorization
Spring Boot 3 + Spring Security 6 - JWT Authentication and Authorisation

```
1) http://localhost:8080/api/v1/auth/register (For Registering)
{
    "firstName":"ananthu",
    "lastName":"vijay",
    "email":"ananthu@gmail.com",
    "password":"ananthu786"
}
```
```
2) http://localhost:8080/api/v1/auth/authenticate
{
    "email":"abhi@gmail.com",
    "password":"abhi123"
}
```
```
3) for accessing the contents after successfull authentication
http://localhost:8080/api/v1/demo-controller
**Note : Use Bearer Token **
```

