# Simple TODO API

 A simple todo app
 
## Prerequisites

- Java 17+
- Maven (or use the included Maven wrapper)

## Getting Started

### 1. Clone the repository
```bash
git clone git@github.com:remsysc/codebility-assessment.git
cd your-repo
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

## API Endpoints

| Method | Endpoint         | Description      |
|--------|-----------------|-------------------|
| GET    | /api/todos       | Get all todos    |
| GET    | /api/todos/{id}  | Get a todo       |
| POST   | /api/todos       | Create a todo    |
| PUT    | /api/todos/{id}  | Update a todo    |
| DELETE | /api/todos/{id}  | Delete a todo    |
