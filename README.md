# cooperative-bank-app
cooperative-bank-app - A modern full-stack banking application for efficient loan management with secure authentication, real-time dashboard analytics, and customer self-service portal.

## 🏦 Cooperative Bank Loan Management System ##
A modern, full-stack web application for efficient loan application management built with React.js and Flask.

✨ Features
🔐 Authentication & Security
JWT-based Authentication - Secure user login with token-based authentication

Role-based Access Control - Different permissions for admin and regular users

Password Hashing - BCrypt encryption for all passwords

Auto-logout - Session management with token expiration

📋 Loan Management
Application Creation - Complete loan application form with validation

Status Tracking - Real-time application status updates

Public Status Check - Customers can check status without login

Document Upload - Support for photo and document submissions

📊 Dashboard & Analytics
Admin Dashboard - Overview of applications, statistics, and metrics

Search & Filter - Advanced search functionality across applications

Activity Tracking - Monitor system activities and user actions

🎨 User Experience
Responsive Design - Works seamlessly on desktop, tablet, and mobile

Intuitive UI - Clean, professional banking interface

Real-time Updates - Instant notifications and status changes

🚀 Quick Start
Prerequisites
Node.js 14+

Python 3.7+

pip package manager

npm or yarn

Installation
Clone the repository

# bash
git clone https://github.com/your-username/cooperative-bank-app.git
cd cooperative-bank-app
Setup Backend

# bash
cd backend
python -m venv venv

# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
pip install -r requirements.txt
Setup Frontend

# bash
cd frontend
npm install

# Run the Application
bash
# From root directory, run both servers
npm run dev

📖 Usage
Login Credentials
Role	Username	Password	Access

# For Customers
Visit the login page

Use "Check Loan Status" for existing applications

Provide application ID and password to view status

# For Bank Staff
Login with admin credentials

Access dashboard for overview

Create new loan applications

View and manage all applications

Update application statuses

