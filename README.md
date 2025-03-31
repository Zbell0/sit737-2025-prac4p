
# SIT737 Practical 4 – Calculator Microservices

This repository contains two independent Node.js-based calculator microservices developed for **SIT737: Cloud-Native Application Development** at Deakin University.

- **4.1P – Basic Arithmetic Calculator**
- **4.2C – Modular Calculator with Controllers and Logging**

---

## Project: 4.1P – Basic Calculator Microservice

### Description
A lightweight Express-based RESTful API that performs basic arithmetic operations.

### How to Run
1. Navigate to the `4.1P` directory  
2. Run `npm install` to install dependencies  
3. Start the server with `node app.js`

### Available Endpoints
- `GET /add`
- `GET /subtract`
- `GET /multiply`
- `GET /divide`

### Usage
Use query parameters `num1` and `num2` with each operation.

Example:  

http://localhost:3000/add?num1=10&num2=5

---

## Project: 4.2C – Modular Calculator Microservice

### Description
A structured calculator API featuring:
- Modular architecture with separate controllers for basic and advanced operations
- Integrated logging using Winston

### How to Run
1. Navigate to the `4.2C` directory  
2. Run `npm install` to install dependencies  
3. Start the development server with `npm run dev`

### Available Endpoints

**Basic Operations**
- `GET /add`
- `GET /subtract`
- `GET /multiply`
- `GET /divide`

**Advanced Operations**
- `GET /power` – Exponentiation  
- `GET /sqrt` – Square root  
- `GET /mod` – Modulo

### Usage
Endpoints accept query parameters like `num1` and `num2`.

Example:  

http://localhost:3000/power?num1=2&num2=3

### Logging
Winston is used for structured logging:
- `logs/combined.log` – All logs (info and error)
- `logs/error.log` – Error logs only

---

## Author

**Ella Kim**  
SIT737 – Cloud-Native Application Development  
Deakin University
