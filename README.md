# College Management System

A comprehensive, full-stack MERN (MongoDB, Express, React, Node.js) web application designed to digitize and streamline institutional campus administration. This portal provides an automated platform to manage classroom organization, academic tracking, user enrollment, and performance analytics across students, teachers, and faculty administrators.

## Features
- **Role-Based Dashboards & Access Control**: Customized user experiences and secure login flows tailored individually for Admins, Teachers, and Students.
- **Admin Management Portal**: Administrative tools to onboard and manage students, assign teachers, create classes, organize subject curriculums, and oversee institution-wide metrics.
- **Teacher Academic Suite**: Empower faculty members to oversee assigned classes, monitor subject enrollments, upload exam marks, and take daily student attendance.
- **Student Performance Hub**: Enables students to view their class schedules, monitor everyday attendance records, and review academic grade histories in real-time.
- **Interactive Visual Analytics**: Integrated analytical charts and data visualizations using Recharts and Material-UI to display attendance percentages and grade distributions.
- **Global State & Secure Architecture**: Built with secure Bcrypt password hashing, RESTful Express APIs, MongoDB schemas, and scalable Redux Toolkit state management.

## Tech Stack
- **JavaScript / Node.js** (Core runtime and backend programming language)
- **MongoDB & Mongoose** (NoSQL document database and Object Data Modeling for campus schemas)
- **Express.js** (Web backend server and RESTful API framework)
- **React.js & React Router DOM** (Frontend UI library and single-page client routing)
- **Redux Toolkit & React-Redux** (Global state management for authentication and academic records)
- **Material-UI (MUI) & Emotion / Styled Components** (Modern UI component library, layout design, and iconography)
- **Recharts** (Dynamic charts and interactive graphical visual analytics)
- **Axios & Bcrypt / Dotenv** (HTTP client communication, secure data encryption, and environment management)

## Installation
```bash
git clone https://github.com/Adithya-P-Vishwamitra/MERN-based-College-Management-System.git
cd MERN-based-College-Management-System

# Install backend server dependencies
cd server
npm install
cd ..

# Install frontend client dependencies
cd client
npm install
cd ..
```

## Usage
```bash
# 1. Configure backend environment
# Create a .env file inside the /server directory and set your database variables:
# MONGO_URL=your_mongodb_connection_string
# PORT=5000

# 2. Start the backend server (runs on port 5000)
cd server
npm start

# 3. Open a separate terminal and start the React frontend client (runs on port 3000)
cd client
npm start
```

## Course Info
Built for [Course Name] at [University], Fall 2026.

## Author
Adithya-P-Vishwamitra
