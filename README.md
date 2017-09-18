# Single Sign On (SSO) Example with JSON Web Token (JWT), Spring Boot

## Guide
https://hellokoding.com/hello-single-sign-on-sso-with-json-web-token-jwt-spring-boot/

## What you'll need
- JDK 1.7+
- Maven 3+

## Stack
- Java
- Spring Boot
- FreeMarker

## Run
- Run Authentication Service: `mvn spring-boot:run`
- Run Resource Service 1: `mvn spring-boot:run -Dserver.port=8180`
- Run Resource Service 2: `mvn spring-boot:run -Dserver.port=8280`

## Add localtest.com domain as 127.0.0.1 in hosts file
## Test
- Open and access browser to "localtest.com:8180"
- Open and access browser to "localtest.com:8280"


