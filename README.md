# Spring Boot REST Service

This project is my first **RESTful API built with Spring Boot**, following the official Spring Getting Started guide.

## 📚 Purpose

The goal of this project is to understand the fundamentals of building a REST API with Spring Boot, including:

* Creating a Spring Boot application
* Building a REST controller
* Mapping HTTP endpoints
* Returning JSON responses
* Using request parameters
* Structuring a basic Spring Boot project

## ⚙️ Technologies

* Java
* Spring Boot
* Maven

## 🧩 Project Structure

```
src/main/java/com/example/restservice
│
├── RestServiceApplication.java   # Spring Boot application entry point
├── GreetingController.java       # REST controller exposing an API endpoint
└── Greeting.java                 # Data record returned as JSON
```

## 🚀 API Endpoint

### GET /greeting

Returns a greeting message.

Example request:

```
http://localhost:8080/greeting
```

Example response:

```json
{
  "id": 1,
  "content": "Hello, World!"
}
```

Using a custom name:

```
http://localhost:8080/greeting?name=David
```

Response:

```json
{
  "id": 2,
  "content": "Hello, David!"
}
```

## 📖 What I Learned

* How to create a REST controller with `@RestController`
* How to define endpoints using `@GetMapping`
* How to read query parameters using `@RequestParam`
* How Spring Boot automatically converts Java objects to JSON
* How to structure a simple REST API project

## 🔜 Next Steps

This repository will continue to evolve as I learn more about:

* Additional REST endpoints
* Request/response handling
* Service layers
* Spring Boot best practices

## 👨‍💻 Author

**Fanampinirina Miharisoa David Fils RATIANDRAIBE**

* GitHub: https://github.com/DavFilsDev


---

Based on the official Spring guide:
https://spring.io/guides/gs/rest-service
