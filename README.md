🏥 Medical Record Dashboard (ASP.NET Core MVC + API + MSSQL)

A complete Medical Record Management System built using ASP.NET Core MVC for the frontend, ASP.NET Core Web API for the backend, and Microsoft SQL Server (MSSQL) for the database.
Users can register, log in, manage profiles, and upload/view medical files securely — all handled via APIs.

🎯 Objective

This project demonstrates a clean, full-stack .NET application architecture with:

Session-based user authentication

Profile management

Medical file upload & preview

Secure backend API integration

MSSQL database with stored procedures

🧱 Project Structure
MedicalRecordSystem/
│
├── Frontend/                     # ASP.NET Core MVC Application
│   ├── Controllers/
│   ├── Models/
│   ├── Views/
│   ├── wwwroot/
│   ├── appsettings.json
│   └── Program.cs
│
├── API/                          # ASP.NET Core Web API
│   ├── Controllers/
│   ├── Models/
│   ├── Services/
│   ├── Repositories/
│   ├── wwwroot/uploads/          # Stored uploaded files
│   ├── appsettings.json
│   └── Program.cs
│
├── Database/                     # Database scripts
│   └── MedicalDB_Script.sql
│
└── README.md
⚙️ Tech Stack
🖥️ Frontend

ASP.NET Core MVC

Bootstrap 5 for responsive UI

jQuery + AJAX for API calls

Session-based Authentication

🧠 Backend

ASP.NET Core Web API

MSSQL Database

ADO.NET with Stored Procedures

File handling in wwwroot/uploads/

💡 Features
👤 User Authentication

Sign Up & Login with:

Full Name

Email

Gender (Male/Female)

Phone Number

Password

🧾 Profile Management

Display and edit user info

Upload/change profile picture

Update email, gender, and phone number

Save profile updates via API

📁 Medical File Upload

File type options:

Lab Report

Prescription

X-Ray

Blood Report

MRI Scan

CT Scan

Upload PDF or image files

Preview uploaded files

View in new tab or modal

Delete files via API

Do u need All files Delete the u can 

login to forget password
