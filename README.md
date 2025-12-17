\# User Authentication Backend



This is a beginner-friendly backend project built using Node.js and Express.js.  

It demonstrates basic user authentication concepts such as user registration, login, password hashing, and API testing using Postman.



---



\## Features

\- User registration

\- User login

\- Password hashing using bcrypt

\- RESTful API structure

\- Basic error handling



---



\## Tech Stack

\- Node.js

\- Express.js

\- JavaScript

\- bcryptjs

\- Postman



---



\## API Endpoints



\### Register User

\*\*POST\*\* `/api/auth/register`



```json

{
  "username": "testuser",
  "password": "123456"
}

```



---



\### Login User

\*\*POST\*\* `/api/auth/login`



```json

{
  "username": "testuser",
  "password": "123456"
}

```



---



\## How to Run Locally



\### 1. Clone the repository

```bash

git clone https://github.com/kshfahmd/auth-backend-node.git

cd auth-backend-node

```



\### 2. Install dependencies

```bash

npm install

```



\### 3. Start the server

```bash

node index.js

```



\### 4. Test APIs

Use \*\*Postman\*\* to test the endpoints listed above.



---



\## Notes

\- User data is stored in memory for learning purposes.

\- This project focuses on understanding backend authentication flow.



