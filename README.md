# File Upload System

## Project Overview

This is a secure file upload system built using Node.js, Express, and Multer. It allows users to upload resume and project files through a web interface. The system validates file type and size before storing files on the server.

---

## Features

- Upload resume and project files
- File type validation (PDF, DOC, DOCX, ZIP)
- File size restriction (up to 5MB)
- Secure backend file handling
- Simple frontend interface
- REST API-based communication

---

## Technologies Used

### Programming Languages
- JavaScript
- HTML
- CSS

### Backend Technologies
- Node.js
- Express.js
- Multer
- CORS
- dotenv (optional)

---

## Project Structure

file-upload-system
-> public
   -> index.html
   -> style.css
   -> script.js

-> routes
   -> uploadRoutes.js

-> uploads
   -> uploaded files

-> server.js
-> package.json
-> package-lock.json
-> .env
-> node_modules

---

## How It Works

### Frontend
The user selects a file from the browser interface and submits it using a form.

### Backend
- The frontend sends the file using an HTTP POST request
- The backend receives the file using Multer middleware
- The file is validated (type and size check)
- If valid, it is stored in the uploads folder
- A response message is sent back to the frontend

### User Feedback
The frontend displays messages such as:
- File uploaded successfully
- Invalid file type
- File too large

---

## API Endpoint

POST /api/upload

This endpoint handles file uploads from the frontend.

---

## Server Port Explanation

The application runs on:

http://localhost:5000

Port 5000 is the communication channel where the Node.js server listens for incoming requests. The browser connects to this port to interact with the backend.

---

## Installation and Setup

### Step 1
Install dependencies

npm install

### Step 2
Run the server

node server.js

### Step 3
Open in browser

http://localhost:5000

---

## Node Modules Used

- express
- multer
- cors
- dotenv

---

## Purpose of Project

This project was created as an internship assignment to demonstrate:

- Backend API development
- File upload handling
- Frontend and backend integration
- Input validation
- Server-side file storage

---

## Future Improvements

- Firebase storage integration
- Database integration for file tracking
- User authentication system
- File management dashboard
- Cloud deployment

---

## Author

Muhammad Hamza  
Software Engineering Student  
Node.js and Cloud Computing Intern  

---

## Links

GitHub Profile  
https://github.com/mhamza3112

LinkedIn Profile  
https://www.linkedin.com/in/mhamza-se 

LinkedIn Project Post  
https://www.linkedin.com/posts/your-post-link  
