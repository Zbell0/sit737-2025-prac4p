[SIT737 PROJECT OVERVIEW]

This repository contains two independent Node.js-based calculator microservices developed for SIT737 Practical 4:

4.1P: A basic arithmetic calculator  
4.2C: A modular calculator with separate controllers and logging

------------------------------------------------------------

[PROJECT: 4.1P - BASIC CALCULATOR MICROSERVICE]

Description:
A simple Express-based calculator that supports basic arithmetic operations via RESTful endpoints.

How to Run:
1. Navigate to the 4.1P directory  
2. Run 'npm install'  
3. Run 'node app.js'

Available Endpoints:
GET /add  
GET /subtract  
GET /multiply  
GET /divide

Usage:
Use query parameters 'num1' and 'num2' for each operation.  
Example: http://localhost:3000/add?num1=10&num2=5

------------------------------------------------------------

[PROJECT: 4.2C - MODULAR CALCULATOR MICROSERVICE]

Description:
A structured calculator microservice with separate basic and advanced controllers, and integrated logging using Winston.

How to Run:
1. Navigate to the 4.2C directory  
2. Run 'npm install'  
3. Run 'npm run dev'

Available Endpoints:

Basic Operations:  
GET /add  
GET /subtract  
GET /multiply  
GET /divide

Advanced Operations:  
GET /power  
GET /sqrt  
GET /mod

Logging:
Winston is used for structured logging.  
logs/combined.log – all logs  
logs/error.log – error logs only

------------------------------------------------------------

[AUTHOR]

Ella Kim  
SIT737 – Cloud-Native Application Development  
Deakin University
