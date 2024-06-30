# TeacherManagement_Backend
Console-based Teacher Management Application to efficiently manage and filter teacher records with comprehensive CRUD operations

## Table of Contents
Overview<br/>
Features<br/>
Technologies<br/>
Requirements<br/>
Installation<br/>
Usage<br/>
API Endpoints<br/>
Screenshots<br/>

## Overview
This project is a console-based Teacher Management Application built using Node.js, Express, and MongoDB. It allows users to perform CRUD operations on teacher records and filter them based on specific criteria. The application provides a user-friendly Console based interface for interaction.

## Features
### 1. Landing/Home Page: A user-friendly landing page with the following options:<br/>

Show all teachers.<br/>
Add a teacher.<br/>
Filter teachers based on criteria.<br/>
Search for a teacher.<br/>
Update a teacher's record.<br/>
Delete a teacher.<br/>

### 2.Teacher’s Record: Each teacher's record includes:<br/>
Full Name of the teacher.<br/>
Age.<br/>
Date of Birth.<br/>
Number of classes he/she teaches.<br/>

### 3.Filter Teachers by Criteria: An option-based page with the following filter options:<br/>
Filter by Age.<br/>
Filter by the number of classes.<br/>

## Techlonogies<br/>
Node.js<br/>
Express<br/>
MongoDB<br/>
Mongoose<br/>
Inquirer.js<br/>
Axios<br/>
dotenv<br/>

## Requirements<br/>
Node.js<br/>
MongoDB<br/>
npm (Node Package Manager)<br/>

## Installation<br/>
### 1. Clone the repository<br/>
git clone https://github.com/yourusername/teacher-management-app.git<br/>
### 2. Navigate to the project directory<br/>
cd teacher-management-app<br/>
### 3. Install dependencies<br/>
npm install<br/>
### 4. Create a .env file in the root directory and add the following environment variables<br/>
PORT=your_port_number<br/>
MONGODB_URL=your_mongodb_connection_string<br/>
### 5. Start the server<br/>
node index.js<br/>

## Usage<br/>
### Running the CLI<br/>
To interact with the application through the command line interface, run<br/>
node cli.mjs<br/>
### CLI Options<br/>
1. Add a new teacher: Prompts for teacher details and adds a new teacher to the database.<br/>
2. Update a teacher: Prompts for teacher ID and new details, then updates the teacher's record.<br/>
3. Delete a teacher: Prompts for teacher ID and deletes the teacher's record.<br/>
4. Fetch all teachers: Retrieves and displays all teacher records.<br/>
5. Fetch a specific teacher: Prompts for teacher ID and retrieves the teacher's record.<br/>
6. Filter teachers: Prompts for filter criteria (age or number of classes) and displays the filtered teacher records.<br/>
7. Exit: Exits the CLI application.<br/>

## API Endpoints<br/>
Add a Teacher : POST /teacher/addTeacher<br/>
Update a Teacher : PUT /teacher/updateTeacher/:id<br/>
Delete a Teacher : DELETE /teacher/deleteTeacher/:id <br/>
Fetch All Teachers : GET /teacher/fetchTeachers<br/>
Fetch Specific Teacher : GET /teacher/fetchPTeacher/:id<br/>
Filter Teachers : GET /teacher/filterTeacher<br/>

## Screenshots<br/>
### Console based Landing page<br/>
![Console Based Landing Page](https://raw.githubusercontent.com/iamsatyamsaurav/Teacher_Mgmt_Backend/main/console_based_interface.png)
<br/>
### Adding a Teacher to the database<br/>
![Add Teacher](https://raw.githubusercontent.com/iamsatyamsaurav/Teacher_Mgmt_Backend/main/add_teacher.png)
<br/>
### Mongodb showing the added teacher's detail<br/>
![MongoDB Add](https://raw.githubusercontent.com/iamsatyamsaurav/Teacher_Mgmt_Backend/main/mongodb_add.png)
<br/>
### Fetching teachers details stored in the database<br/>
![Fetch Teacher](https://raw.githubusercontent.com/iamsatyamsaurav/TeacherManagement_Backend/main/fetch_teacher.png)
