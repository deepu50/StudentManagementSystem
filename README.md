# StudentManagementSystem
I have developed a laravel application for student management system

In this I have used xampp for the apache server and sql connection.

step-1:after cloning the project from git do composer update

step-2 create a database and update it in the env file

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=student_management
DB_USERNAME=root
DB_PASSWORD=

step-2:php artisan migrate
step-3:php artisan serve


This application manages a student details and their academic performance .In this we have provision to add the student details ,
edit their details and delete their details .Also we have a Crud to keep track of student performance in subject
