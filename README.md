
# 📊 SIT737 Practical 4 – Calculator Microservices (4.1P & 4.2C)

This repository contains two separate calculator microservice projects developed as part of SIT737 Cloud-Native Application Development practical tasks.

---

## 📁 Project Structure

sit737-2025-prac4p/
├── 4.1P/
│   ├── app.js
│   └── package.json
│
├── 4.2C/
│   ├── app.js
│   ├── controllers/
│   │   ├── basicController.js
│   │   └── advancedController.js
│   ├── logger.js
│   ├── logs/
│   └── package.json

---

## 🧮 4.1P – Basic Calculator Microservice

### 📌 Description
A simple Node.js calculator app exposing basic arithmetic operations using REST endpoints.

### ▶️ How to Run

```bash
cd 4.1P
npm install
node app.js

🚀 Endpoints

Method	Endpoint	Description
GET	/add	Addition
GET	/subtract	Subtraction
GET	/multiply	Multiplication
GET	/divide	Division

Use query parameters num1 and num2, e.g.:

GET http://localhost:3000/add?num1=10&num2=5



⸻

🔧 4.2C – Modular Calculator Microservice (Advanced)

📌 Description

An enhanced version of the calculator app with:
	•	Separated controllers (basic and advanced)
	•	Logging using Winston
	•	Modular and scalable code structure

▶️ How to Run

cd 4.2C
npm install
npm run dev

🧪 API Endpoints

Basic Operations
	•	/add, /subtract, /multiply, /divide

Advanced Operations
	•	/power – Exponentiation
	•	/sqrt – Square root
	•	/mod – Modulo

🗂 Logging (via Winston)
	•	logs/error.log – error-level logs
	•	logs/combined.log – all logs

