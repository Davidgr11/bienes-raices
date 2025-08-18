# Real Estate MVC 🏡

Real Estate MVC is a web application designed for property management, allowing users to publish, manage, and search for real estate listings efficiently and securely. The project is built following the Model-View-Controller (MVC) architecture pattern, which ensures scalability, maintainability, and clean code organization.

## Project Overview

The platform allows users to:
- Register and authenticate securely.
- Publish new properties with images and relevant details.
- Edit, delete, and manage their own properties.
- Search for properties using various filters (category, price, location, etc.).
- Send and receive messages related to properties.

The system is designed to be intuitive, responsive, and secure, integrating modern web development best practices and a user-friendly experience.

## Technologies Used

- **Node.js**: JavaScript runtime environment for server-side development.
- **Express.js**: Web framework for Node.js, used for routing and HTTP request handling.
- **Sequelize**: ORM for managing the MySQL database, simplifying model interactions and migrations.
- **MySQL**: Relational database system for storing users, properties, categories, prices, and messages.
- **Pug**: Template engine for generating dynamic and reusable views.
- **Tailwind CSS**: Utility-first CSS framework for modern, responsive UI design.
- **Webpack**: Module bundler for static assets and resources.
- **Nodemailer**: Email sending for password recovery and notifications (optional, depending on configuration).
- **bcrypt**: Secure password hashing for user credentials.
- **JWT (JSON Web Tokens)**: Secure authentication and authorization using tokens.
- **Google Maps API**: Map integration to display property locations.

## Key Features

- MVC architecture for better organization and scalability.
- Robust form validation and error handling.
- Image management and file uploads.
- Secure password and session management.
- Modern, mobile-friendly user interface.
- Advanced property search and filtering.
- Admin dashboard for registered users.

## Project Structure

- `/controllers`: Business logic and route controllers.
- `/models`: Database models and relationships.
- `/views`: Dynamic views using Pug.
- `/public`: Static files (CSS, JS, images).
- `/routes`: Application route definitions.
- `/helpers`: Utility functions and helpers.
- `/middleware`: Custom middleware for authentication and file handling.
- `/config`: Database and service configuration.
- `/seed`: Files to populate the database with initial data.

## Author
Developed by David G. for learning purposes, portfolio, and as a professional Node.js web application example.

---

Thank you for checking out this project! If you have any feedback or suggestions, feel free to contact me on LinkedIn.
