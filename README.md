# Role-Based MERN Web Application

This project is a role-based web application built using the MERN stack (MongoDB, Express.js, React, Node.js). It implements a flexible user role system with three distinct roles: user, admin, and superadmin. Each role has different levels of access and permissions to manage notes and users.

## Key Features
 ### User Roles:
   Roles are assigned based on users' email IDs after login. Each role has different permissions:
   - **User** : Can create, read, update, and delete their own notes.
   - **Admin** : Can add or remove users and delete users' notes.
   - **Superadmin** : Has the highest level of control; can remove users and delete any data within the application.

 ### User Authentication:
 - Users can sign up and log in using their email and password.
 - JWT (JSON Web Token) is used for authentication, and bcryptjs ensures secure password hashing.

 ### Frontend:
- Built with ReactJS and styled using Bootstrap, providing a responsive and interactive user experience.

 ### Backend:
- Powered by Node.js and Express, using RESTful APIs to handle authentication and CRUD operations in MongoDB database.

## Technologies Used:

- **Frontend**: ReactJS, Bootstrap, HTML, CSS, Javascript
- **Backend**: Node.js, Express.js
- **Database**:  MongoDB
- **Authentication**: JWT, bcryptjs
