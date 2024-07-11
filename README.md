# Student Management API

This API provides endpoints for managing student data, including retrieving, adding, deleting, updating grades, and calculating GPA.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Endpoints](#endpoints)
  - [Get the list of all students](#1-get-the-list-of-all-students)
  - [Get data about a single student by name](#2-get-data-about-a-single-student-by-name)
  - [Add a new student](#3-add-a-new-student)
  - [Delete a student by ID](#4-delete-a-student-by-id)
  - [Update the grade of a student by name and class name](#5-update-the-grade-of-a-student-by-name-and-class-name)
  - [Get the GPA of a student](#6-get-the-gpa-of-a-student)
- [Running the Application](#running-the-application)
- [Dependencies](#dependencies)

## Installation
1. Clone the repository:
   ```sh
   git clone <repository_url>
   cd <repository_directory>
2. Install the dependencies:
   ```sh
   npm install

## Usage
1. Start the server:
    ```sh
    node <filename>.js
3. The application will listen on port 8080.

## EndPoints
1. Get the list of all students : GET /students
2. Get data about a single student by name : GET /students/:name
3. Add a new student : POST /students
4. Delete a student by ID : DELETE /students/:id
5. Update the grade of a student by name and class name : PUT /students/:name/:class/:grade
6. Get the GPA of a student : GET /students/:name/gpa

## Running the Application
To run the application, use the following command:
```sh
node <filename>.js

## Dependencies
1. express
2. body-parser
3. uuid

You can install the dependencies using the following command:
```sh
 npm install express body-parser uuid






