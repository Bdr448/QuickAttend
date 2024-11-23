

---

# 🎉 **QuickAttend**  
**QuickAttend** is a modern and efficient Android application for managing attendance. Designed with teachers and students in mind, it simplifies attendance tracking, reporting, and management.  

---

## 🌟 **Features**  
### 👨‍🏫 For Teachers:
- 🔑 **Generate Attendance Code**: Create random, time-sensitive attendance codes valid for 5 minutes.  
- 📊 **Export Attendance Reports**: Download detailed attendance sheets in Excel format.  
- 🔒 **Secure Login**: Dedicated teacher login interface for role-based access.  

### 👩‍🎓 For Students:
- 📝 **Mark Attendance**: Enter the provided code, subject, and date to log attendance securely.  
- 🎯 **Easy-to-Use Interface**: A simple and intuitive design for quick access.  

### 🎨 General:
- ✨ **Custom Animation**: Displays a welcoming animation: "Welcome to QuickAttend!"  
- 📶 **Offline Support**: Functions seamlessly without internet using local SQLite storage.  

---

## 🚀 **Advantages**
- ⏱️ **Time-Saving**: Eliminate manual attendance-taking processes.  
- 🔐 **Secure**: Code-based authentication ensures only authorized users can access features.  
- 📈 **Detailed Reports**: Export attendance data as Excel files for easy analysis.  
- 💻 **User-Friendly**: Intuitive UI designed for simplicity and efficiency.  

---

## ⚙️ **How It Works**  
1. 👨‍🏫 **Teacher Workflow**:  
   - Log in and generate a unique attendance code.  
   - Share the code with students.  

2. 👩‍🎓 **Student Workflow**:  
   - Log in, input the attendance code, subject, and date.  

3. 📂 **Data Management**:  
   - Export attendance data to Excel for record-keeping.  

4. ✨ **Animation**:  
   - Start-up animation greets users with "Welcome to QuickAttend!"  

---

## 🧠 **App Logic**
1. 🎲 **Random Code Generation**:  
   - Teachers generate secure codes using Kotlin's random functions.  

2. ⏳ **Time Validation**:  
   - Codes automatically expire after 5 minutes for security.  

3. 💾 **Local Data Storage**:  
   - Attendance data is stored using SQLite, ensuring offline functionality.  

4. 📜 **Excel Export**:  
   - Leverages Apache POI to create attendance reports in Excel format.  

5. 🔒 **Role-Based Authentication**:  
   - Separate login portals for teachers and students.  

---

## 🖼️ **Screenshots**  
### 🔑 **Login Screen**  
![Login Screen](./assets/screenshots/login_screen.png)  

### 👨‍🏫 **Teacher Dashboard**  
![Teacher Dashboard](./assets/screenshots/teacher_dashboard.png)  

### 👩‍🎓 **Student Dashboard**  
![Student Dashboard](./assets/screenshots/student_dashboard.png)  

---

## 🛠️ **Technologies Used**
- 💻 **Programming Language**: Kotlin  
- 🗄️ **Database**: SQLite  
- 📊 **Excel Export**: Apache POI library  
- 🎨 **UI Design**: XML layouts  
- 🔧 **Version Control**: Git & GitHub  

---

## 📦 **Setup Instructions**
1. Clone the repository:  
   ```bash
   git clone https://github.com/Bdr448/QuickAttend.git
   ```
2. Navigate to the project directory:  
   ```bash
   cd QuickAttend
   ```
3. Open the project in Android Studio.  
4. Sync Gradle and install dependencies.  
5. Build and run the app on an emulator or a physical device.  

---

## 📈 **Future Enhancements**
- ☁️ **Cloud Integration**: Add real-time syncing with cloud databases.  
- 🔔 **Push Notifications**: Send attendance reminders to students.  
- 📊 **Analytics**: Offer insights and trends in attendance patterns.  

---

## 🤝 **Contributors**
- **[bhavya raval]** - Developer  

---

---
