# DocPro: Appointment Scheduling for Clinics/Hospitals

DocPro is a web application built using the MERN stack (MongoDB, Express.js, React, Node.js) with additional technologies such as Redux, bcryptjs, Bootstrap, and Ant Design. This project was developed during the period from April 2023 to May 2023.

## Project Overview

DocPro aims to streamline the process of doctor appointment scheduling for clinics and hospitals. The application provides a user-friendly platform where individuals can register, log in, and seamlessly schedule appointments with preferred doctors based on their specialization. The authentication process is managed using JWT tokens to ensure user security.

Hosted link
https://docpro.onrender.com/

## Key Features

- **User Authentication**: Users can register and log in securely with JWT token authentication.
  
- **Appointment Scheduling**: Users can apply for appointments with doctors of their choice, specifying their preferred specialization, date, and time.

- **Doctor Application**: Users can apply to become doctors by filling out a form. Admin approval is required, and once approved, users are assigned the role of a doctor.

- **Admin Control**: Admins have the authority to approve or reject doctor applications, block users, and have access to a comprehensive list of all doctors and users.

- **Distinct UI for Different Roles**: Each role (user, doctor, admin) has a unique user interface tailored to their specific needs.

- **CRUD Operations with Redux Toolkit**: All CRUD (Create, Read, Update, Delete) operations are implemented using React Redux Toolkit.

- **Notification System**: Notifications are sent through POST requests, and users are mapped accordingly.

## Project Motivation

The motivation behind DocPro stems from the common issue of patients having to endure long waiting periods in physical queues. To address this problem, DocPro allows users to schedule appointments at their preferred times, reducing the waiting period and enhancing the overall healthcare experience.

## Technologies Used

- React
- Redux
- Node.js
- MongoDB
- bcryptjs
- Express.js
- Bootstrap
- Ant Design
- JavaScript

## How to Run

1. Clone the repository.
2. Install dependencies using `npm install` in both the client and server directories.
3. Configure the MongoDB connection in the server.
4. Run the server using `npm start` in the server directory.
5. Run the client using `npm start` in the client directory.

Feel free to explore and contribute to making DocPro an even more efficient and user-friendly solution for doctor appointment scheduling

Home Page
![image](https://github.com/sourajsarkar/project1/assets/98710029/6950b1cf-fc7b-4b67-8770-082fdb56a906)

User can also apply for doctor
![image](https://github.com/sourajsarkar/project1/assets/98710029/82d9c9a9-8d2f-47ff-9b4f-d56e540d5cd1)

