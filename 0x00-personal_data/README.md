Personal Data Management Project
This project focuses on developing a secure backend system for managing personal data, with an emphasis on authentication, data encryption, and logging.

Overview
This project aims to create a backend system that handles personal data securely. It covers various aspects of data management, including logging, encryption of passwords, and database connectivity. By completing this project, you will gain practical experience in building robust and secure systems for handling sensitive information.

Requirements
Ubuntu 18.04 LTS
Python 3.7
pycodestyle version 2.5 for code style adherence
mysql-connector-python for database connectivity
bcrypt package for password hashing
All code files should be executable and end with a new line.
Documentation for all modules, classes, and functions, explaining their purpose in a clear sentence.
Type annotations for all functions.
Tasks
0. Regex-ing
Write a function filter_datum that obfuscates log messages using regex.

1. Log Formatter
Update RedactingFormatter class to accept a list of fields constructor argument and implement the format method to filter values in incoming log records using filter_datum.

2. Create Logger
Implement get_logger function to return a logging.Logger object named "user_data" with specific logging configurations.

3. Connect to Secure Database
Implement get_db function to connect securely to a MySQL database using environment variables for credentials.

4. Read and Filter Data
Implement main function to retrieve and display data from a database in a filtered format.

5. Encrypting Passwords
Implement hash_password function to securely hash passwords using the bcrypt package.

6. Check Valid Password
Implement is_valid function to validate passwords using bcrypt.

License
This project is licensed under the MIT License. See the LICENSE file for details.
