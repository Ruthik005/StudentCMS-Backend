
# StudentCMS-Backend


## Getting Started

1. Change the Directory:

```bash
cd server
```

2. Install dependencies:

```bash
npm install nodemon 
npm install mongodb
npm i cors
npm i express
npm i nodemailer
```

3. Run the Server:

```bash
nodemon app.js
```

## API Endpoints

The application exposes the following API endpoints:

- **Registration:** `/registration/signup` (POST)
- **Login:** `/login/signin` (POST)
- **View Courses:** `/viewcourses` (GET)
- **Add Course:** `/book/addnewcourse` (POST)
- **Delete Course:** `/deletecourse` (DELETE)
- **View Students:** `/viewstudents` (GET)
- **Add Student:** `/addstudent` (POST)
- **View Faculty:** `/api/faculty` (GET)
- **Add Faculty:** `/addfaculty` (POST)
- **Delete Faculty:** `/deletefaculty/:id` (DELETE)
- **View Feedback:** `/viewfeedback` (GET)
- **Submit Feedback:** `/feedback` (POST)
- **Submit Attendance:** `/submitattendance` (POST)
- **View Attendance:** `/viewattendance` (GET)
- **Send OTP (Password Reset):** `/sendotp` (POST)
- **Reset Password:** `/resetpassword` (POST)
- **Send Email:** `/sendemail` (POST)
