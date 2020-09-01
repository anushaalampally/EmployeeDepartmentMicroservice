# EmployeeDepartmentMicroservice


This project is to get handson on Microservices.
Java Microservices with Spring Boot and Spring Cloud


Our sample microservices-based system consists of the following modules:

-gateway-service - a module that Spring Cloud Netflix Zuul for running Spring Boot application that acts as a proxy/gateway in our architecture.

-employee-service - a module containing the first of our sample microservices that allows to perform CRUD operation on JPA repository of employees(MySQL)

-department-service - a module containing the second of our sample microservices that allows to perform CRUD operation on JPA repository of departments(MySQL). It communicates with employee-service.
