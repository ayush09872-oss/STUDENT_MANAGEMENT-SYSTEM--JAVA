# Student Performance Management System

A simple console-based Java application for managing student records, marks, attendance, and performance reports.

The project is designed as a beginner-friendly Java project using core Java concepts such as classes and objects, ArrayList, file handling, exception handling, and menu-driven programming.

## Features

### Student Management
- Add a student
- View all students
- Search a student by roll number
- Update student information
- Delete a student
- Prevent duplicate roll numbers

### Marks Management
- Enter marks for Java, Mathematics, and English
- Calculate total marks
- Calculate average marks
- Calculate grade
- Validate marks from 0 to 100

### Attendance Management
- Record total classes
- Record attended classes
- Calculate attendance percentage
- Check attendance eligibility
- Validate attendance values

### Reports and Dashboard
- Generate an individual student performance report
- Generate a class performance dashboard
- Display class average
- Display the highest-performing student
- Display attendance statistics
- Display performance categories

### Data Storage
- Save student information in a local text file
- Load saved data when the program starts
- Keep data available after restarting the application

## Technologies Used

- Java
- Object-Oriented Programming
- ArrayList
- Java Collections Framework
- File Handling
- Exception Handling
- Git and GitHub
- Visual Studio Code or any Java-supported IDE

## Project Structure

```text
Student-Performance-Management-System/
│
├── src/
│   ├── Main.java
│   ├── Student.java
│   ├── StudentManager.java
│   ├── MarksManager.java
│   ├── AttendanceManager.java
│   ├── ReportManager.java
│   ├── DashboardManager.java
│   ├── FileManager.java
│   └── InputValidator.java
│
├── docs/
│   ├── Test-Cases.md
│
├── Screenshots/
│
├── Project-Report/
│   └── Student-Performance-Management-System.pdf
│
├── students.txt
├── README.md
└── .gitignore
```

## Requirements

Before running the project, make sure Java is installed.

Check Java:

```bash
java -version
```

Check the Java compiler:

```bash
javac -version
```

The project uses standard Java features and does not require any external libraries.

## How to Run from the Terminal

The project is intended to be compiled and run directly from the terminal.

### 1. Clone the repository

```bash
git clone https://github.com/[your user name]/Student-Performance-Management-System.git
```

### 2. Open the project folder

```bash
cd Student-Performance-Management-System
```

### 3. Compile the Java files

Create a separate folder for compiled files:

```bash
mkdir out
```

Then compile the source files.

#### Windows

```bash
javac -d out src\*.java
```

#### macOS / Linux

```bash
javac -d out src/*.java
```

### 4. Run the application

Run this command from the project root:

```bash
java -cp out Main
```

Running the program from the project root is important because `students.txt` is stored there and is used for data persistence.

### 5. Use the menu

After starting the program, use the menu displayed in the terminal.

The application currently includes options for:

1. Add Student
2. View Students
3. Search Student
4. Update Student
5. Delete Student
6. Add Marks
7. View Performance
8. Record Attendance
9. View Attendance
10. Generate Performance Report
11. Class Performance Dashboard
12. Exit

## Data Storage

Student data is stored in:

```text
students.txt
```

The file contains student details along with marks and attendance information.

The program loads the saved data when it starts and updates the file when student information changes.

## Input Validation

The application checks for invalid input such as:

- Non-numeric values where numbers are required
- Marks outside the range 0 to 100
- Negative attendance values
- Attendance greater than the total number of classes
- Empty student names
- Duplicate roll numbers

## Author

Student Performance Management System developed as an academic Java project.
