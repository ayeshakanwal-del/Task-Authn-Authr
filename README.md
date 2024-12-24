# Task-Authn-Authr
It is the repo for Authentication task


# Authentication_Authorization-

1.User registration with hashed passwords.
2.User login with password validation.
3.Routes to handle these functionalities.
4.Session-based authentication.

Register Users:

Users submit a POST request to /api/users/register with their username and password.
Backend checks if the username already exists.
If not, it hashes the password and stores the user in the database.

Log In Users:

Users submit a POST request to /api/users/login with their credentials.
Backend verifies the username and password.
If valid, it creates a session for the user.