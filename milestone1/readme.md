# Milestone 1 – User Authentication System (PolicyNav)

## Description

In this milestone, we developed a secure user authentication system for the PolicyNav application using Streamlit, JWT (JSON Web Tokens), and MongoDB Atlas. The system enables users to create accounts, log in securely, reset forgotten passwords using security questions, and access a protected dashboard after authentication.


## Features Implemented

- User Signup with validation  
- Secure Login using JWT  
- Dashboard after login  
- Forgot Password functionality  
- Password Reset using JWT token and security question
- Ngrok Integration
- MongoDB Atlas database integration  



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

## Screenshots

- Signup Page
  <img width="1918" height="962" alt="image" src="https://github.com/user-attachments/assets/5198d209-2026-4120-b4ec-e6e2d81591ef" />

- Login Page
  <img width="1918" height="967" alt="image" src="https://github.com/user-attachments/assets/837e98d3-2cf8-47d1-a835-37b93a51e0dd" />

- Dashboard
  <img width="1918" height="965" alt="image" src="https://github.com/user-attachments/assets/3ef2a1e6-6e94-4298-9f3b-a23daee02aec" />


- Forgot Password Page
  <img width="1918" height="963" alt="image" src="https://github.com/user-attachments/assets/4007f52c-79db-4d04-a678-0d7329fa2dfd" />

- Reset Password Page
  <img width="1918" height="967" alt="image" src="https://github.com/user-attachments/assets/c0f41b11-0f5f-41b1-b1aa-0c35822de8f1" />
  <img width="1918" height="965" alt="image" src="https://github.com/user-attachments/assets/acd6a415-7cb7-41e2-aa57-1212d00ee3df" />

## Notes
- JWT is used for session management and password reset flow.
- MongoDB Atlas is used as the cloud database.
