# Job Portal

Job Portal is a MERN Stack based web app which helps in streamlining the flow of job application process. It allows users to select there roles (applicant/recruiter), and create an account. In this web app, login session are persistent and REST APIs are securely protected by JWT token verification. After logging in, a recruiter can create/delete/update jobs, shortlist/accept/reject applications, view resume and edit profile. And, an applicant can view jobs, perform fuzzy search with various filters, apply for jobs with an SOP, view applications, upload profile picture, upload resume and edit profile. Hence, it is an all in one solution for a job application system.

### SignUp-Page
![see](https://github.com/ayush461/JOB-MANAGEMENT/assets/69451578/90d980fe-0fb5-4e33-bda9-ecae17139b05)

### Login-Page
<img width="951" alt="lg" src="https://github.com/ayush461/JOB-MANAGEMENT/assets/69451578/8ffe8307-8ee2-47a7-a67d-b33f7e77c6cb">

### Applications
![applications](https://github.com/ayush461/JOB-MANAGEMENT/assets/69451578/c9db7b3f-745d-497b-b45b-3d8323854f50)

### Jobs-Page
![multiplejobs](https://github.com/ayush461/JOB-MANAGEMENT/assets/69451578/2c071f77-7816-4ca4-b4aa-e51475d4ab11)

###  My-Jobs
![jobs](https://github.com/ayush461/JOB-MANAGEMENT/assets/69451578/e1637600-b34a-41c7-b953-0cf999bd2041)

### Job-Posting
![addjob](https://github.com/ayush461/JOB-MANAGEMENT/assets/69451578/9183c080-9043-423d-bff3-c3f541b2f067)

Directory structure of the web app is as follows:

```
- backend/
    - public/
        - profile/
        - resume/
- frontend/
- README.md
```

## Instructions for initializing web app:

- Install Node JS, MongoDB in the machine.
- Start MongoDB server: `sudo service mongod start`
- Move inside backend directory: `cd backend`
- Install dependencies in backend directory: `npm install`
- Start express server: `npm start`
- Backend server will start on port 4444.
- Now go inside frontend directory: `cd ..\frontend`
- Install dependencies in frontend directory: `npm install`
- Start web app's frontend server: `npm start`
- Frontend server will start on port 3000.
- Now open `http://localhost:3000/` and proceed creating jobs and applications by signing up in required categories.

## Dependencies:

- Frontend
  - @material-ui/core
  - @material-ui/icons
  - @material-ui/lab
  - axios
  - material-ui-chip-input
  - react-phone-input-2
- Backend
  - bcrypt
  - body-parser
  - connect-flash
  - connect-mongo
  - cors
  - crypto
  - express
  - express-session
  - jsonwebtoken
  - mongoose
  - mongoose-type-email
  - multer
  - passport
  - passport-jwt
  - passport-local
  - uuid

# Machine Specifications

Details of the machine on which the webapp was tested:

- Operating System: Elementary OS 5.1 (Hera)
- Terminal: Bash
- Processor: Intel Core i7-8750H CPU @ 2.20 GHz 2.21 GHz
- RAM: 16 GB
