# Milestone 1 – User Authentication System (PolicyNav)

## Description

In this milestone, we developed a secure user authentication system for the PolicyNav application using Streamlit, JWT (JSON Web Tokens), and MongoDB Atlas. The system enables users to create accounts, log in securely, reset forgotten passwords using security questions, and access a protected dashboard after authentication.

---

## Features Implemented

- User Signup with validation  
- Secure Login using JWT  
- Dashboard after login  
- Forgot Password functionality  
- Password Reset using JWT token and security question  
- MongoDB Atlas database integration  

---

## How to Run

1. Install required dependencies  
   ```bash
   pip install streamlit pymongo pyjwt
2. Run the Streamlit application
   ```bash
   streamlit run app.py
3. Use ngrok to expose the application (if required)
   ```bash
   ngrok http 8501
---
## Screenshots
(Add your screenshots here)
Signup Page
Login Page
Dashboard
Forgot Password Page
## Notes
Passwords are stored in plain text for Milestone-1 demonstration purposes only.
JWT is used for session management and password reset flow.
MongoDB Atlas is used as the cloud database.
