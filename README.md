<h1 align="center">📘 Student Record Management System</h1>

<p align="center">
A simple, lightweight, and powerful C-based project to manage student records using file handling and role-based access control.
</p>

---

## 🚀 About the Project
This **Student Record Management System** is a console application written in C to perform basic operations on student records such as:

- ➕ Add Student
- 📋 Display All Students
- 🔎 Search by Roll Number
- ✏️ Update Student Data
- ❌ Delete Student (Admin Only)

It uses **text files** for storage, making it easy to run on any system without database installation.

---

## 🎯 Key Features

### 🔐 Login System
- Username & Password Authentication
- Role-Based Access

### 👥 User Roles
Each user role has different permissions:

| Feature    | Admin | Staff | User | Guest |
|-----------|:-----:|:-----:|:----:|:-----:|
| Add       | ✔️     | ✔️     | ❌    | ❌     |
| Display   | ✔️     | ✔️     | ✔️    | ✔️     |
| Search    | ✔️     | ✔️     | ✔️    | ✔️     |
| Update    | ✔️     | ✔️     | ❌    | ❌     |
| Delete    | ✔️     | ❌     | ❌    | ❌     |

### 📁 File Handling
- `students.txt` → Student Database
- `credentials.txt` → Login Credentials

---

## 🏗️ Project Structure

```
Student_Record_Management_System/
│
├── README.md
├── student_app.c
├── credentials.txt
└── students.txt
```

---

## ⚙️ How It Works

1️⃣ Start Program  
2️⃣ Enter Username & Password  
3️⃣ System Validates Login  
4️⃣ Loads Appropriate Menu  
5️⃣ Perform Operations  
6️⃣ Save Data to File  
7️⃣ Logout  

---

## 🗂️ File Formats

### 🔐 credentials.txt
```
username password role
admin admin123 admin
staff staff123 staff
user user123 user
guest guest123 guest
```

### 🧾 students.txt
```
roll name marks
1 John 78.5
2 Maya 88.0
3 Alex 90.0
```

---

## 🛠️ Compilation & Execution

### Compile:
```sh
gcc student_app.c -o student_app
```

### Run:
```sh
./student_app
```

---

## 🧠 Flowchart

```
START
  |
LOGIN
  |
VALID USER? -> NO -> Retry/Exit
  |
LOAD MENU
  |
OPERATIONS
  |
LOGOUT
  |
END
```

---

## 🖥️ Sample Output

```
=====================================
       STUDENT RECORD SYSTEM
=====================================
USERNAME : admin
PASSWORD : admin123

✔ Login successful! Logged in as: admin
```

---

## 🌟 Future Enhancements

- ⭐ Hidden Password
- ⭐ Sorting Options
- ⭐ GUI Version
- ⭐ CSV Export
- ⭐ Color UI
- ⭐ Statistics Dashboard

---

## 🙌 Ideal For

- 🎓 Students Learning C
- 🧪 File Handling Lab Projects
- 🧠 Beginners in Programming
- 🏫 Diploma/Degree Mini Projects

---

<p align="center"><b>Made with ❤️ in C</b></p>

