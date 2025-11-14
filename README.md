# Backend-Experiment2: User Registration Form

## Steps

### 1. Import Database
Create database user_registration_db and table users in phpMyAdmin:
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50) NOT NULL,
    email VARCHAR(100) NOT NULL,
    password VARCHAR(255) NOT NULL
);

### 2. Place Files
Put all files in:
MAMP: /Applications/MAMP/htdocs/experiment2

Files:
- db_connect.php
- register.html
- register.php

### 3. Run
MAMP:
http://localhost:8888/experiment2/register.html
