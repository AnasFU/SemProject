# SemProject
This is the a simple web application          
first:create SQL-Login-Project

1:Create the SQL Database

    Open XAMPP and start Apache and MySQL.

    Open phpMyAdmin (http://localhost/phpmyadmin).

    Click New, name the database **RegistrationSystem_DB**, and click Create.

    Click SQL and run this query to create a users table:

                    CREATE TABLE users (
                    id INT AUTO_INCREMENT PRIMARY KEY,
                    username VARCHAR(50) NOT NULL,
                    password VARCHAR(255) NOT NULL
                );
