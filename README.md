# WebAssignment02
Course Registration System
Project Overview
The Course Registration System is a web-based platform that allows students to log in, browse available courses, register for courses, and manage their schedules. Administrators can log in to manage courses, student registrations, seat availability, and generate reports.

The system is built using Node.js, Express.js, MongoDB, and JavaScript, with a frontend using HTML, CSS, and JavaScript.

Features
Student Features
Login: Students log in using their roll number (pre-existing in the database).
Course Registration: Students can register for available courses.
Real-Time Seat Availability: The system updates seat availability dynamically.
Interactive Weekly Calendar: Students can view their schedules and avoid conflicts.
Course Filtering: Students can filter courses by department, time, days, and seat availability.
Prerequisite Checking: The system verifies prerequisites before allowing registration.
Session Persistence: Students' course selections persist throughout their session.
Admin Features
Login: Admins log in using a username and password.
Course Management: Admins can add, update, or delete courses and set prerequisites.
Student Management: Admins can view and override student registrations if necessary.
Seat Management: Admins can adjust available seats for courses.
Reports: Generate reports for registered students, available courses, and prerequisite completion.
Technology Stack
Backend
Node.js - JavaScript runtime
Express.js - Backend framework
MongoDB - NoSQL database
Mongoose - MongoDB ORM
JWT (JSON Web Token) - Authentication
bcrypt.js - Password hashing
dotenv - Environment variable management
Frontend
HTML, CSS, JavaScript - UI and interactivity
Fetch API - Handles API requests
LocalStorage - Stores session data
