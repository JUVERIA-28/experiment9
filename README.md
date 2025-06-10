# Student CRUD API with Express.js

## Description
A simple Express.js REST API that allows CRUD operations on student data.

## How to Run

1. Install Node.js
2. Run the following in terminal:

```bash
npm init -y
npm install express
node index.js
```

3. Use Postman to test the API at `http://localhost:3000/students`

## API Endpoints

| Method | URL             | Description        |
|--------|------------------|--------------------|
| GET    | /students        | Get all students   |
| GET    | /students/:id    | Get one student    |
| POST   | /students        | Add student        |
| PUT    | /students/:id    | Update student     |
| DELETE | /students/:id    | Delete student     |
