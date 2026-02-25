# Simple TODO API

 A simple todo app
 
## Prerequisites

- Java 17+
- Maven (or use the included Maven wrapper)

## Getting Started

### 1. Clone the repository
```bash
git clone git@github.com:remsysc/codebility-assessment.git
cd codebility-assessment/backend/
```

### 2. Run the application
```bash
./mvnw clean compile spring-boot:run
```

> **Windows users:** use `mvnw.cmd clean compile spring-boot:run`

### 3. The API will be available at
```
http://localhost:8080
```
## Postman Documentation
```
https://documenter.getpostman.com/view/46218722/2sBXcGEf7j
```

## API Endpoints

| Method | Endpoint         | Description         |
|--------|-----------------|----------------------|
| GET    | /api/v1/todos       | Get all todos    |
| GET    | /api/v1/todos/{id}  | Get a todo       |
| POST   | /api/v1/todos       | Create a todo    |
| PUT    | /api/v1/todos/{id}  | Update a todo    |
| DELETE | /api/v1/todos/{id}  | Delete a todo    |
