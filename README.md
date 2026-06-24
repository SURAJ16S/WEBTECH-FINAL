# 🌐 Web Technology Final Assignments

A comprehensive collection of web development assignments demonstrating a progressive learning curve from fundamental Frontend basics to advanced Backend APIs and modern Frontend Frameworks (React.js).

This repository serves as a complete Web Technology portfolio, categorized into 8 distinct assignments.

---

## 📂 Repository Structure & Progression

### 🔹 Core Frontend Fundamentals
* **Assignment 1:** `Static HTML Page`
  - Explores the structure of modern web pages using raw HTML. Includes semantic tags and deep layout structures.
* **Assignment 2:** `Vanilla JS Todo Application` (`todo.html`)
  - Introduces DOM manipulation using Vanilla JavaScript. Users can dynamically add and manage tasks on the client side.
* **Assignment 3:** `JSON Parsing & Data Fetching` (`index.html`, `data.json`)
  - Demonstrates how to fetch and render structured data from a JSON payload dynamically.

### 🔹 Server-Side Scripting & Databases
* **Assignment 4:** `PHP & MySQL` (`index.php`, `sqldb.sql`)
  - Transitions into server-side programming. Demonstrates connecting a PHP script to a MySQL database schema and executing basic data retrieval queries.

### 🔹 Modern Frontend Framework (React.js)
* **Assignment 5:** `React Component State` (`ReactPropsUsestate/`)
  - Dives into React fundamentals. Demonstrates passing `props` between components and managing component lifecycle data using the `useState` hook.
* **Assignment 6:** `React HTTP Requests` (`Axios/`)
  - Explores network requests in modern frameworks. Demonstrates how to integrate the popular `axios` library inside React to fetch and render API data.
* **Assignment 7:** `React Form Validation` (`formvalidation/`)
  - Covers complex form handling in React. Implements robust client-side validation logic to ensure data integrity before submission.

### 🔹 Backend API Development (Node.js)
* **Assignment 8:** `Express.js RESTful API` (`server.js`, `package.json`)
  - A full standalone Express.js backend application serving a static UI and providing complete CRUD (Create, Read, Update, Delete) operations over a `students` dataset.
  - **Endpoints:**
    - `GET /` - Serves the main UI
    - `GET /students` - Fetches the student list
    - `POST /students` - Adds a new student
    - `PUT /students/:id` - Updates existing student data
    - `DELETE /students/:id` - Removes a student

---

## 🚀 How to Run the Projects

### Running Static/Vanilla Assignments (1, 2, 3)
Simply open the `.html` files in any modern web browser. For Assignment 3, you may need to use a local live server (like VS Code's Live Server extension) to avoid CORS issues when fetching the local JSON file.

### Running PHP Assignment (4)
1. Install a local server environment like XAMPP, WAMP, or MAMP.
2. Place the `Assignment 4` folder into your `htdocs` or `www` directory.
3. Import the `sqldb.sql` file into your local MySQL database via phpMyAdmin.
4. Navigate to `http://localhost/Assignment 4/index.php`.

### Running React Assignments (5, 6, 7)
Each React assignment has its own `package.json`. Navigate into the specific assignment directory and run:
```bash
npm install
npm start
```
This will start the React development server, typically accessible at `http://localhost:3000`.

### Running Node.js Backend Assignment (8)
1. Navigate into the `Assignment 8` directory.
2. Install the necessary backend dependencies:
```bash
npm install
```
3. Start the Express server:
```bash
node server.js
```
4. Access the REST API or UI at `http://localhost:3000`.

---
*Created as part of a Web Technology Curriculum.*
