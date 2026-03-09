# DocSpot – Doctor Appointment Booking System

DocSpot is a full-stack web application that allows patients to book doctor appointments online.
The system supports three roles: **User (Patient), Doctor, and Admin**. Each role has specific functionalities for managing appointments, profiles, and system operations.

The application is built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**.

---

## Project Overview

DocSpot simplifies the process of booking and managing doctor appointments. Patients can easily find doctors, check availability, and schedule appointments. Doctors can manage appointment requests, and administrators control the overall system.

---

## Tech Stack

### Frontend

* React.js
* HTML5
* CSS3
* JavaScript
* Axios

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Other Tools

* JWT Authentication
* REST APIs
* Git & GitHub

---

## User Roles and Features

### 1. User (Patient)

* Register and login
* View list of doctors
* Book appointments
* View appointment history
* Manage profile

### 2. Doctor

* Login to doctor dashboard
* View appointment requests
* Accept or reject appointments
* View patient details
* View total earnings

### 3. Admin

* Manage doctors
* Approve doctor registrations
* View all users
* Monitor appointments
* Manage system data

---

## Installation and Setup

### 1. Clone the repository

```
git clone https://github.com/your-username/DocSpot.git
```

### 2. Navigate to the project folder

```
cd DocSpot
```

### 3. Setup Backend

```
cd backend
npm install
```

Create a `.env` file and add:

```
PORT=5000
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run backend server:

```
npm start
```

---

### 4. Setup Frontend

```
cd frontend
npm install
npm start
```

The application will run at:

```
http://localhost:3000
```

---

## API Functionalities

* User authentication
* Doctor management
* Appointment booking
* Appointment approval and rejection
* Profile management

---

## Future Improvements

* Online payment integration
* Video consultation
* Email/SMS notifications
* Doctor availability calendar
* Mobile application

---

## Author

**Ranjitha**
BSc Computer Science Graduate
Full Stack Developer

---

## License

This project is developed for learning and portfolio purposes.
