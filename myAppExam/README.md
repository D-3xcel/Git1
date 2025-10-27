# 🎓 Student Enrollment System (Laravel Project)
## 📝 Description / Overview
The **Student Enrollment System** is a web-based Laravel application designed to simplify and digitalize the student registration process. It allows administrators to manage student records efficiently while reducing paperwork and human error.

## 🎯 Objectives
- To automate the student registration and enrollment process.  
- To provide a user-friendly interface for managing student information.  
- To allow easy access, editing, and retrieval of student records.  
- To practice applying Laravel MVC structure and CRUD operations.  

## ⚙️ Features / Functionality
- 🧑‍🎓 Add, view, update, and delete student profiles.  
- 📋 Manage student details such as name, age, address, and date of birth.  
- 🧑‍🏫 Assign subjects and teachers to students.  
- 🔍 Search and filter functions for faster data management.  
- 📱 Responsive and modern design using Blade templates.  

## 💽 Installation Instructions via command prompt:
1. Clone or download this repository:
    git clone https://github.com/D-3xcel/Git1.git

2. Navigate to the project folder:
    cd myAppExam

3. Install dependencies:
    composer install
    npm install

4. Set up your .env file and configure your database.
copy .env.example .env
<!--Then open .env and update your database details:-->

<!--Copy code-->
DB_CONNECTION=mysql 
DB_HOST=127.0.0.1 
DB_PORT=3307 
DB_DATABASE=myAppExam 
DB_USERNAME=root 
DB_PASSWORD= 

5. Generate application key:
    php artisan key:generate

6. Run migrations:
    php artisan migrate

7. Start the local development server:
    php artisan serve

8. Open your browser and visit:
    http://localhost:8000

<!-- Note: This project uses MySQL on port 3307, as configured in the .env file-->

🚀 Usage
- Open the web app and log in as admin.
- Add or edit student details using the navigation menu.
- Assign subjects and teachers as needed.
- View all registered students and their details from the dashboard.

🖼️ Screenshots or Code Snippets
Example Blade Template Snippet:
<!-- Example Blade template -->
@extends('layouts.app')

@section('content')
<h1>Student List</h1>
<table>
  <tr><th>Name</th><th>Section</th><th>Action</th></tr>
  <!-- Student data rows go here -->
</table>
@endsection

👨‍💻 Contributors
- Dan Excel Rosales

📜 License
- This project is licensed under the MIT License – you are free to use, modify, and distribute it for educational purposes.
- © 2025 Dan Excel Rosales. All rights reserved.