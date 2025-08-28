## Overview

- The Exam Hall Management System is a web-based application developed using PHP, MySQL, HTML, CSS, and JavaScript.
-  This system is designed to help educational institutions manage exam halls efficiently.
-  It automates tasks such as student seating allocation, hall assignments, and exam schedules, reducing manual errors and improving administrative efficiency.

## Features

## Admin Panel

- Add, edit, and remove exam halls.

- Add and manage students and exam schedules.

- Generate seating arrangements automatically.

## Student Management

- Register and maintain student records.

- Assign students to specific exam halls.

## Exam Scheduling

- Create and manage exam schedules.

- Prevent conflicts in hall allocation and timing.

## Seating Arrangement

- Generate hall-wise seating charts.

- Easily printable seating plans for exam supervisors.

## Security

- Admin login authentication.

- Secure database storage of sensitive student and exam information.

## Technologies Used

- Backend: PHP

- Database: MySQL

- Frontend: HTML, CSS, JavaScript

- Server: XAMPP/WAMP/LAMP

## Installation Steps

1. Clone the Repository

   git clone https://github.com/Prethika88/Exam-Hall-Management-System.git

2. Move to Project Directory

   cd exam-hall-management-system

3. Set up Database

-  Open phpMyAdmin and create a database, e.g., exam_hall_db.

-  Import the SQL file exam_hall_db.sql included in the project.

4. Configure Database Connection

 - Open config.php and set your database credentials:

   $servername = "localhost";
   
   $username = "root";
   
   $password = "";
   
   $dbname = "exam_hall_db";

5. Run the Project

- Start Apache and MySQL via XAMPP/WAMP/LAMP.

- Open your browser and navigate to:

  http://localhost/exam-hall-management-system/

## Usage

- Admin can log in and manage all aspects of exam hall scheduling and student seating.

- Students can view their assigned hall and seat number.

- Admin can generate printable hall-wise seating charts.
