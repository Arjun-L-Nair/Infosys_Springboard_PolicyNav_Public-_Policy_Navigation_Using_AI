# Milestone 2 – OTP Authentication,Admin Interface,Readability Dashboard

## Description

In this milestone, we developed a secure user authentication system for the PolicyNav application using Streamlit, JWT (JSON Web Tokens), and SQL Lite. The system enables users to create accounts, log in securely, reset forgotten passwords using security questions, and access a protected dashboard after authentication.
Integrated otp verification for account login,signup.Added Admin dashboard with some privileges and a Readability dashboard.

## Features Implemented

- OTP-based authentication

- Account lock after 3 wrong password attempts (5-minute lock)

- Secure Forgot Password (no reuse of old passwords) - Password History

- Admin Login + Admin Dashboard

- Readability Dashboard 
## How to Run

1. Install required dependencies  
   ```bash
   pip install streamlit pyngrok pyjwt watchdog dotenv bcrypt PyPDF2 streamlit-option-menu readability-lxml textstat plotly
2. Run the Streamlit application
   ```bash
   streamlit run app.py
3. Use ngrok to expose the application (if required)
   ```bash
   ngrok http 8501

## Screenshots

- Signup Page
  <img width="1918" height="967" alt="image" src="https://github.com/user-attachments/assets/d519ed27-5125-408a-a8c9-936be853d0de" />

- Login Page
  <img width="1918" height="967" alt="image" src="https://github.com/user-attachments/assets/837e98d3-2cf8-47d1-a835-37b93a51e0dd" />
  
- OTP Verification Page
  <img width="1918" height="966" alt="image" src="https://github.com/user-attachments/assets/cce47ae5-bbe5-40a8-92e8-4d27f7c8e2ec" />
  
- Admin Dashboard
  <img width="1918" height="967" alt="image" src="https://github.com/user-attachments/assets/896f31b6-52a8-48fe-b2b6-bb51294b1e24" />
  <img width="1918" height="966" alt="image" src="https://github.com/user-attachments/assets/82c65618-152a-4d53-a3f0-85a560141ec5" />

- User Dashboard
  <img width="1918" height="963" alt="image" src="https://github.com/user-attachments/assets/330c81fe-c993-4fcd-87e3-3a43117f1832" />

- Readability Dashboard
  <img width="1918" height="967" alt="image" src="https://github.com/user-attachments/assets/6adfee42-9fe4-4c66-8dd6-eebd67334fac" />

- Forgot Password Page
  <img width="1918" height="966" alt="image" src="https://github.com/user-attachments/assets/39b6cc00-fd11-4851-a5df-3db6145c3656" />
  <img width="1918" height="966" alt="image" src="https://github.com/user-attachments/assets/2c266a68-63d2-48ab-86e9-2286e3863065" />

- Reset Password Page
<img width="1918" height="967" alt="image" src="https://github.com/user-attachments/assets/cb5466b4-df7e-4752-b9d3-59de9b718a39" />

## Notes
- JWT is used for session management and password reset flow.
- Added Readability Dashboard,Admin Dashboard.
- Changed the database from MongoDB Atlas to SqLite
