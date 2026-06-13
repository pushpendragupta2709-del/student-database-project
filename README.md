# Student Management System

A web-based **Student Management System** built using **Python Flask** and **SQLite**. This application allows administrators to manage student records, attendance, marks, and generate PDF reports through a simple web interface.

## Features

* Admin Login Authentication
* Add New Students
* Edit Student Details
* Delete Student Records
* Search Students by Name
* Manage Student Attendance
* Add Subject-wise Marks
* Generate PDF Reports
* SQLite Database Integration
* Responsive Dashboard

## Technologies Used

* Python 3
* Flask
* SQLite3
* HTML
* CSS
* JavaScript
* ReportLab (PDF Generation)

## Project Structure

```
Student-Management-System/
│
├── app.py
├── students.db
├── report.pdf
│
├── templates/
│   ├── login.html
│   ├── index.html
│   └── edit.html
│
├── static/
│   ├── style.css
│   └── script.js
│
└── README.md
```

## Installation

### 1. Clone Repository

```bash
git clone https://github.com/your-username/student-management-system.git
cd student-management-system
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

### 3. Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install flask reportlab
```

### 5. Run Application

```bash
python app.py
```

### 6. Open Browser

```
http://127.0.0.1:5000
```

## Default Login Credentials

Username:

```
admin
```

Password:

```
admin123
```

## Database Tables

### Students

* id
* name
* age
* course

### Attendance

* id
* student_id
* status
* date

### Marks

* id
* student_id
* subject
* marks

## Future Enhancements

* Student Photo Upload
* Role-Based Authentication
* Email Notifications
* Attendance Analytics
* Marks Visualization Charts
* Cloud Database Integration

## Author

Pushpendra Gupta 

## License

This project is created for educational and learning purposes.
