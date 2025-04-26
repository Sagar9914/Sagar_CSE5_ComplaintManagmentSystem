# Complaint Management System

## 👥 Team Members
- Sagar (2301010312)
- Shivansh (2301010314)
- Devesh Sharma (2301010317)
- Yash Singh (2301010339)

## 📋 Project Description
The Complaint Management System is a full-stack web application built to simplify the complaint registration and resolution process.  
It allows users to submit complaints via **written form** or **voice recording**, generates a **unique complaint ID** for tracking, sends **real-time email notifications** to admins, provides **chatbot support**, collects **user reviews**, and displays complaint locations on an **interactive map**.  
The system is designed to be **user-friendly**, **responsive**, and **transparent**.

---

## 🚦 Steps of the Project (System Flow)

1. **User accesses the Complaint Form** — available on the website.
2. **User submits complaint** — by filling out a text form or recording a voice complaint.
3. **Backend server processes the complaint** — stores it in the MySQL database.
4. **System generates a Unique Complaint ID** — shown to the user for tracking purposes.
5. **Email Notification** — the system sends an instant email to the admin with complaint details.
6. **Complaint Tracking** — users can check the status (Pending, Completed, Deleted) using their Complaint ID.
7. **Chatbot Assistance** — users can ask the chatbot questions like "How to register a complaint?" for guidance.
8. **Feedback and Review** — users can submit star ratings and reviews after complaint handling.
9. **Interactive Map** — users or admins can click on a city name to view the complaint’s geographic location on a map.

---

## 📹 Link to Video Explanation
[Insert your video explanation link here]

Example:  
➡️ [Watch the Project Walkthrough](https://drive.google.com/your-video-link)

---

## ⚙️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript (ES6+)

### Backend
- Node.js
- Express.js

### Database
- MySQL

### Other Tools and Libraries
- Nodemailer (for email notifications)
- Multer (for voice file uploads)
- Google Maps API / OpenStreetMap (for map integration)
- React-Toastify (for notification alerts)
- Figma (for UI/UX wireframes)
- Custom Chatbot Script

---

## 🚀 Steps to Run/Execute the Project

Follow these simple steps to set up and run the Complaint Management System on your local machine:

Step 1. Clone the Repository
```bash
git clone [Your GitHub Repository Link]

Step 2:
cd complaint-management-system

step 3:
cd frontend
npm install

step 4:
cd ../backend
npm install

Step 5:
CREATE DATABASE complaint_db;

DB_HOST=your_database_host
DB_USER=your_database_username
DB_PASSWORD=your_database_password
DB_NAME=complaint_db
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password

step 6:
npm run dev

step 7:
cd ../frontend
npm start


Open your browser and visit:
http://localhost:3000
