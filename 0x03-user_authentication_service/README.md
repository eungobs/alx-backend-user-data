User Authentication Service
This project aims to implement a user authentication service using Python, SQLAlchemy, Flask, and bcrypt. It provides various functionalities such as user registration, login, session management, password hashing, and password reset.

Project Structure
The project is organized into several tasks, each addressing specific functionalities:

User Model
Define a SQLAlchemy model for the User with attributes like id, email, hashed_password, session_id, and reset_token.
Create User
Implement a method to add a new user to the database.
Find User
Implement a method to find a user by specific criteria.
Update User
Implement a method to update user attributes in the database.
Hash Password
Define a method to hash passwords using bcrypt.
Register User
Implement a method to register a new user, including password hashing.
Basic Flask App
Set up a basic Flask app with a GET route to return a welcome message.
Credentials Validation
Implement a method to validate user login credentials.
Generate UUIDs
Define a method to generate UUIDs for various purposes.
Get Session ID
Implement a method to create a session ID for a user.
Log In
Implement a route to handle user login requests.
Find User by Session ID
Implement a method to find a user by session ID.
Destroy Session
Implement a method to destroy a user session.
Log Out
Implement a route to handle user logout requests.
User Profile
Implement a route to fetch user profile information.
Generate Reset Password Token
Implement a method to generate a reset password token.
Get Reset Password Token
Implement a route to get a reset password token.
Update Password
Implement a method to update a user's password.
Update Password End-Point
Implement a route to update a user's password.

Dependencies
Python 3.x
SQLAlchemy
Flask
bcrypt
Contributor: Elizabeth Eunice Ndzukule
Collaborator Name
License
This project is licensed under the MIT License - see the LICENSE file for details.
