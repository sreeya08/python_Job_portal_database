# Job Portal Management System

## Project Description

The Job Portal Management System is a Python-based console application designed to manage recruitment-related information such as candidates, companies, jobs, skills, applications, and interviews.

The project is developed using Python and Jupyter Notebook. Instead of using a database, the project stores and manages data using a text file named `job_portal_data.txt`.

The application provides a menu-driven interface where users can perform different operations related to job management and recruitment.

---

## Project Features

The Job Portal Management System provides the following features:

* View candidate details
* Add new candidates
* View company details
* View available jobs
* Search jobs by location
* Apply for jobs
* Check application status
* Update application status
* View interview details
* Generate hiring reports
* Store and read data using a TXT file

---

## Technologies Used

* Python
* Jupyter Notebook
* TXT File Handling

---

## Python Concepts Used

This project demonstrates the following Python concepts:

* Variables
* Lists
* Dictionaries
* Functions
* Loops
* Conditional Statements
* User Input
* String Operations
* File Handling
* Exception Handling

---

## Project Modules

### 1. Candidates

This module manages candidate information such as:

* Candidate ID
* Candidate Name
* Email
* Phone Number
* Qualification
* Experience
* City

---

### 2. Companies

This module manages company information such as:

* Company ID
* Company Name
* Industry
* Location

---

### 3. Jobs

This module manages available job information such as:

* Job ID
* Company ID
* Job Title
* Salary
* Location

---

### 4. Skills

This module stores different skills required in the job portal.

Examples include:

* Python
* Java
* SQL
* HTML
* CSS
* JavaScript
* React
* Machine Learning
* AWS

---

### 5. Applications

This module manages job applications submitted by candidates.

It stores:

* Application ID
* Candidate ID
* Job ID
* Application Date
* Application Status

Application status can be:

* Pending
* Selected
* Rejected

---

### 6. Interviews

This module manages interview-related information.

It stores:

* Interview ID
* Application ID
* Interview Date
* Interview Result

Interview results can include:

* Pass
* Fail
* Pending

---

## Project Structure

```text
Job_Portal_Project/
│
├── Job_Portal_System.ipynb
├── job_portal_data.txt
└── README.md
```

### Job_Portal_System.ipynb

Contains the complete Python code for the Job Portal Management System.

### job_portal_data.txt

Stores the project data for:

* Candidates
* Companies
* Jobs
* Skills
* Applications
* Interviews

### README.md

Contains information about the project, features, technologies, and instructions for running the project.

---

## How the Project Works

```text
User
  ↓
Python Menu
  ↓
User Selects an Option
  ↓
Python Functions Process the Request
  ↓
Read or Update Data
  ↓
Display Result
  ↓
Return to Menu
```

---

## How to Run the Project

### Step 1: Install Python

Make sure Python is installed on your system.

### Step 2: Install Jupyter Notebook

Install Jupyter Notebook using:

```bash
pip install notebook
```

### Step 3: Download or Copy the Project Files

Make sure the following files are in the same folder:

```text
Job_Portal_System.ipynb
job_portal_data.txt
```

### Step 4: Open Jupyter Notebook

Open the terminal or command prompt and run:

```bash
jupyter notebook
```

### Step 5: Open the Notebook

Open:

```text
Job_Portal_System.ipynb
```

### Step 6: Run All Cells

Run the notebook cells in order.

### Step 7: Use the Menu

The program will display the Job Portal menu.

Select an option and enter the required details.

---

## Example Menu

```text
================================
       JOB PORTAL SYSTEM
================================

1. View Candidates
2. Add Candidate
3. View Companies
4. View Jobs
5. Search Jobs
6. Apply for Job
7. Check Application Status
8. Update Application Status
9. View Interview Details
10. Hiring Report
11. Exit
```

---

## Data Storage

The project uses a text file named:

```text
job_portal_data.txt
```

The file contains different sections:

```text
[CANDIDATES]

[COMPANIES]

[JOBS]

[SKILLS]

[APPLICATIONS]

[INTERVIEWS]
```

Python reads the information from the text file and processes it using lists and dictionaries.

---

## System Flow

```text
START
  ↓
LOAD DATA FROM TXT FILE
  ↓
DISPLAY MAIN MENU
  ↓
USER SELECTS AN OPTION
  ↓
PROCESS THE REQUEST
  ↓
DISPLAY RESULT
  ↓
RETURN TO MENU
  ↓
EXIT
```

---

## Team Members

* M. Sreeya
* B. Harika
* V. Sai Charan

---

## Future Enhancements

The project can be improved in the future by adding:

* Graphical User Interface using Tkinter
* User Login and Registration
* Job Posting Functionality
* Resume Upload
* Advanced Search Options
* Email Notifications
* Data Visualization and Charts
* Database Integration

---

## Conclusion

The Job Portal Management System is a Python-based project that demonstrates important programming concepts such as functions, lists, dictionaries, loops, conditional statements, and file handling.

The project provides a simple and organized way to manage candidates, companies, jobs, applications, and interview information using Python and a TXT file.

This project demonstrates how Python can be used to create a practical real-world application without using a database.
