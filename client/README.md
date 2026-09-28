# icsi418y-pa2
Thanisha Raj
Csi418 second assignment : Signin and Login

Description: 
This project provides user signup and login functionality. The frontend is built using React, while the backend uses Node.js and Express. MongoDB is used to store and retrieve user account information.

The application allows a new user to create an account by entering their first name, last name, username, and password. The backend validates the submitted information and checks MongoDB to make sure the username is not already being used. If the username is available, the new user is added to the database.

The login page allows an existing user to enter their username and password. The backend searches MongoDB for the username and compares the submitted password with the stored password. The application then displays a message indicating whether the login was successful or unsuccessful.

The application also handles errors such as missing fields, duplicate usernames, incorrect passwords, nonexistent usernames, and server or database errors.

Instructions: User types in the input field their name and preferred username and password. Once that is completed and entered, user can then login using their username and password that they just provided