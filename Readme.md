# RESTful API Assignment - Node.js & Express

## Objective
Build a simple RESTful API for managing a list of users using Node.js and Express. This assignment tests concepts such as routing, middleware, HTTP methods, status codes, error handling, and interaction with a data source.

---

## Requirements

### 1. Initialize a Node.js project (5 marks)
- Setup a new Node.js project.
- Install Express.

### 2. Define a REST API with the following routes (25 marks)
- `GET /users` – Fetch the list of all users.
- `GET /users/:id` – Fetch details of a specific user by ID.
- `POST /user` – Add a new user.
- `PUT /user/:id` – Update details of an existing user.
- `DELETE /user/:id` – Delete a user by ID.

### 3. Sample User Object Structure
```json
{
  "id": "1",
  "firstName": "Anshika",
  "lastName": "Agarwal",
  "hobby": "Teaching"
}
```

### 4. Middleware (30 marks)
- **Logging Middleware (15 marks)**: Log details of each request (method, URL, status code).
- **Validation Middleware (15 marks)**: Check for required fields (`id`, `firstName`, `lastName`, `hobby`) in the `POST` and `PUT` routes.

### 5. Error Handling (10 marks)
- Return appropriate HTTP status codes (`200`, `404`, `201`, `400`).
- Handle errors such as "user not found" and "invalid input" with meaningful messages.

### 6. Data Source
- Store user data in-memory using an array.

---

## Submission Guidelines (30 marks)
- **Code Comments (5 marks)**: Include clear comments explaining the logic.
- **API Testing (25 marks)**: Test the API using Postman or Thunder Client and include screenshots of the results.
- **Submission Format**: Submit a ZIP folder containing your code and a document with test result screenshots.

---

### Instructions for Running the Project
1. **Initialize the project**
   ```sh
   npm init -y
   npm install express
   ```
2. **Run the server**
   ```sh
   node RESTAPI.js
   ```
3. **Test API endpoints** using Postman/Thunder Client.

Happy coding! 🚀