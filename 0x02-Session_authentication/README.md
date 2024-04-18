# 0x02. Session Authentication

## Project Description

This project aims to implement a session authentication mechanism without using any additional modules, strictly for learning purposes. Session authentication is a widely used method to manage user sessions in web applications, allowing users to remain logged in across multiple requests without repeatedly providing credentials.

## Background Context

In this project, I Have implemented session authentication, a fundamental aspect of web application security. Session authentication involves generating and managing session IDs for authenticated users, typically stored in cookies. Unlike basic authentication, which requires sending credentials with each request, session authentication allows users to stay logged in for extended periods by associating a unique session ID with each user's session.

## Tasks

### 0. Et moi et moi et moi!

Copy the work from the previous "Basic authentication" project to create a basic authentication system.

### 1. Empty session

Create a `SessionAuth` class inheriting from `Auth`. This class will be the foundation for the session authentication mechanism.

### 2. Create a session

Update the `SessionAuth` class to create and manage session IDs for users.

### 3. User ID for Session ID

Implement a method in the `SessionAuth` class to retrieve a user ID based on a session ID.

### 4. Session cookie

Add functionality to retrieve a session ID from a request's cookie in the `Auth` class.

### 5. Before request

Update the `@app.before_request` method to handle session authentication for protected routes.

### 6. Use Session ID for identifying a User

Enhance the `SessionAuth` class to retrieve a user instance based on a session ID.

### 7. New view for Session Authentication

Create a new Flask view to handle authentication requests using session IDs.

### 8. Logout

Implement a method to log out users by destroying their session.

## Repository Information

- **GitHub Repository:** [alx-backend-user-data](https://github.com/eungobs/alx-backend-user-data)
- **Directory:** 0x02-Session_authentication

## Files

- `api/v1/app.py`: Main Flask application file.
- `api/v1/views/session_auth.py`: Flask view file for session authentication.
- Other necessary Python scripts for authentication and user management.
