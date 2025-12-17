\# User Authentication Backend



This is a beginner-friendly backend project built using Node.js and Express.js.

The project demonstrates basic user authentication concepts such as user registration, login, password hashing, and API testing using Postman.



\## Features

\- User registration

\- User login

\- Password hashing using bcrypt

\- RESTful API structure

\- Basic error handling



\## Tech Stack

\- Node.js

\- Express.js

\- JavaScript

\- bcryptjs

\- Postman



\## API Endpoints



\### Register User

POST /api/auth/register



Request Body:

{

&nbsp; "username": "testuser",

&nbsp; "password": "123456"

}



\### Login User

POST /api/auth/login



Request Body:

{

&nbsp; "username": "testuser",

&nbsp; "password": "123456"

}



\## How to Run Locally

1\. Clone the repository

2\. Install dependencies:

&nbsp;  npm install

3\. Start the server:

&nbsp;  node index.js

4\. Test APIs using Postman



\## Notes

\- User data is stored in memory for learning purposes.

\- This project focuses on understanding backend authentication flow.



