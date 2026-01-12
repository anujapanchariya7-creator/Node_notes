Q1. Role of Frontend (FE)
The Frontend (FE) is the part of a web application that users directly see and interact with. It runs in the user’s browser and focuses on presentation and usability.

1. User Interface (UI)

The frontend is responsible for designing and displaying the user interface.

It includes layout, colors, fonts, buttons, forms, and responsiveness.

Technologies commonly used are HTML (structure), CSS (styling), and JavaScript (behavior).

A good UI ensures clarity, accessibility, and a visually appealing experience.

2. User Interaction

The frontend handles all user interactions such as clicks, form submissions, scrolling, and input validation.

It provides immediate feedback to users (e.g., error messages, loading indicators).

JavaScript frameworks like React, Angular, and Vue help manage complex interactions efficiently.

3. Communication with Backend

The frontend communicates with the backend through APIs (usually REST or GraphQL).

It sends requests (HTTP methods like GET, POST, PUT, DELETE) and receives responses (often in JSON format).
-----------------------------------------------------------
Q2. Role of Backend (BE)

The Backend (BE) is the server-side part of a web application. It handles logic, data processing, and security, and is not directly visible to users.

1. Server-Side Processing

The backend processes requests received from the frontend.

It applies business rules, performs calculations, and controls application flow.

Backend code runs on servers using languages such as JavaScript (Node.js), Java, Python, or PHP.

2. Database Handling

The backend interacts with databases to store, retrieve, update, and delete data.

It works with relational databases (MySQL, PostgreSQL) or NoSQL databases (MongoDB).

It ensures data consistency and integrity.

3. Security and Authentication

The backend handles user authentication and authorization.

It protects sensitive data using encryption, tokens (JWT), and secure protocols.

It prevents unauthorized access, SQL injection, and other security threats.
--------------------------------------------------------------
Q3. Business Logic

Business Logic refers to the rules, conditions, and decision-making processes that define how a business operates within a software application.

Explanation

It represents the core functionality of an application.

Business logic determines what happens to data and how workflows are executed.

It is usually implemented in the backend (or application layer) to ensure consistency and security.

Real-World Examples

E-commerce Website

Calculating the final price after applying discounts, taxes, and shipping charges.

Allowing free shipping only if the order value exceeds a certain amount.

Banking Application

Restricting withdrawals if the account balance is insufficient.

Applying different interest rates based on account type.

Online Exam System

Automatically submitting the exam when time expires.

Calculating results based on correct and incorrect answers.
------------------------------------------------------------

Q4. Client–Server Model

The Client–Server Model is a network architecture where tasks are divided between service requesters (clients) and service providers (servers).

1. Client

The client is the user-facing component, such as a web browser or mobile app.

It sends requests for data or services.

Example: Chrome browser accessing a website.

2. Server

The server is a system that processes client requests and provides responses.

It hosts applications, databases, and APIs.

Example: A web server running Node.js or Java.

3. Communication Process

Communication occurs over the internet using protocols like HTTP/HTTPS.

The client sends a request → the server processes it → the server sends a response.

Data is commonly exchanged in JSON or XML format.

--------------------------------------------------------------

Q5. Three-Tier Architecture

Three-Tier Architecture divides a web application into three distinct layers to improve scalability, maintainability, and security.

1. Presentation Layer

This is the frontend layer.

It handles UI and user interactions.

Technologies: HTML, CSS, JavaScript, React, Angular.

2. Application (Business) Layer

This layer contains business logic and application rules.

It processes requests from the presentation layer.

Technologies: Node.js, Spring Boot, Django.

3. Data Layer

This layer manages data storage and retrieval.

It includes databases and data access logic.

Technologies: MySQL, PostgreSQL, MongoDB.

Why This Architecture Is Used

Separation of concerns makes the application easier to maintain.

Each layer can be scaled independently.

Improves security by isolating data access from the UI.
---------------------------------------------------------

Q6. JavaScript as a Backend Language

JavaScript is widely used as a backend language, especially with Node.js, due to several advantages.

1. Performance

Node.js uses a non-blocking, event-driven architecture.

It handles multiple requests efficiently with low latency.

Suitable for real-time applications like chat apps and APIs.

2. Ecosystem

JavaScript has a vast ecosystem with npm (Node Package Manager).

Thousands of libraries and tools are available for backend development.

Faster development due to reusable packages.

3. Popular Backend Frameworks

Express.js – Lightweight and flexible framework for APIs.

NestJS – Structured, scalable framework inspired by Angular.

Fastify – High-performance backend framework.

Using JavaScript on both frontend and backend allows developers to build full-stack applications with a single language, improving productivity and consistency.