# QuickAttend

**QuickAttend** is a modern attendance management Android application designed to simplify and streamline the attendance process for educational institutions. The app features a user-friendly interface, separate logins for teachers and students, and a secure system for attendance tracking with real-time code generation and Excel report export capabilities.

---

## Features

### For Teachers
- **Secure Login**: Teachers can log in to their dedicated interface.
- **Attendance Code Generation**: Generate a unique, random attendance code valid for 5 minutes, ensuring security.
- **Excel Report Export**: Export detailed attendance records in Excel format for easy tracking and analysis.
- **User-Friendly Dashboard**: Intuitive controls for managing attendance codes and viewing records.

![Teacher Dashboard](./screenshots/teacher_dashboard.png)

### For Students
- **Simple Login**: Students can log in using their credentials to access their interface.
- **Mark Attendance**: Enter the attendance code, subject, and date to mark attendance.
- **Real-Time Validation**: Attendance codes are validated within the 5-minute window.

![Student Login](./screenshots/student_login.png)

### General
- **Interactive Animation**: Displays a "Welcome to QuickAttend!" animation upon opening the app.
- **Offline Support**: Stores data locally and syncs with the database when internet connectivity is restored.
- **Attractive UI**: Clean and well-organized design for seamless navigation.

![Welcome Animation](./screenshots/welcome_animation.gif)

---

## Advantages

1. **Secure and Accurate**:
   - Unique codes ensure that only present students can mark attendance.
   - Time-bound codes prevent misuse.

2. **Efficient and Paperless**:
   - Eliminates the need for manual attendance, reducing errors and saving time.
   - All records are stored digitally for easy access.

3. **Detailed Reports**:
   - Teachers can download attendance reports in Excel format for future reference and analysis.

4. **User-Friendly**:
   - Intuitive design for both teachers and students, ensuring ease of use.

5. **Scalable**:
   - Designed to handle growing users and institutions.

---

## App Screenshots

### Login Screen
![Login Screen](./screenshots/login_screen.png)

### Teacher Dashboard
![Teacher Dashboard](./screenshots/teacher_dashboard.png)

### Student Dashboard
![Student Dashboard](./screenshots/student_dashboard.png)

---

## How it Works

1. **Teacher’s Side**:
   - Log in to the app using teacher credentials.
   - Generate a random attendance code valid for 5 minutes.
   - Share the code with students in the classroom.
   - Export the attendance details to an Excel file.

2. **Student’s Side**:
   - Log in to the app using student credentials.
   - Enter the attendance code, subject, and date.
   - Submit the details to mark attendance.
   - Attendance is validated based on the code’s validity.

---

## Logic and Technologies Used

1. **Attendance Code Logic**:
   - A random numeric code is generated and stored in the database.
   - The code is valid for 5 minutes and cannot be reused.

2. **Excel Export**:
   - Attendance records are exported using a library that converts data into `.xlsx` format.

3. **Database**:
   - SQLite is used for local storage.
   - Firebase or other cloud services can be integrated for real-time synchronization.

---

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Bdr448/QuickAttend.git
