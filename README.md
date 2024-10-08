# Cobapaz

- [Cobapaz](#cobapaz)
  - [Overview](#overview)
  - [Demo](#demo)
  - [Features](#features)
    - [Institutional Website](#institutional-website)
    - [Login System](#login-system)
    - [Registration System](#registration-system)
    - [Account Recovery System](#account-recovery-system)
    - [Student Dashboard](#student-dashboard)
    - [Admin Dashboard](#admin-dashboard)
    - [404 Error](#404-error)
  - [Technologies](#technologies)

## Overview
**Cobapaz** is a **Payment by Reference System** designed to simplify the management of tuition fees at a private educational institution. The system enables students to generate payment references, while the administration can monitor the status of these transactions through an intuitive administrative dashboard.

## Demo
You can view the project demo running [by clicking here](https://youtu.be/aHl0_Pbi4S4).

## Features

### Institutional Website
- **Home Page:** The landing page of the system that provides an overview and quick access to key functionalities.
  
  ![Home](./assests/img/home.png)
  ![Home about](./assests/img/home-about.png)
  ![Home courses](./assests/img/home-courses.png)
  ![Home School](./assests/img/home-school.png)

- **Courses Page:** A dedicated page listing all courses offered by the institution, allowing students to explore available options.

  ![Courses](./assests/img/courses.png)

- **Contact Page:** Provides contact information for the institution, facilitating communication between students and administration.

  ![Contacts](./assests/img/contacts.png)

- **Footer:** The system's footer that includes important links and information about the institution.

  ![Footer](./assests/img/footer.png)

### Login System
- **Login Form:** The interface that allows students to authenticate into the system using their credentials.

  ![Signin](./assests/img/signin.png)
  ![Signin Loading](./assests/img/signin-loading.png)

### Registration System
- **Registration Form:** Used to register new students, gathering the necessary information for account creation.

  ![Signup Page 1](./assests/img/signup-page-1.png)
  ![Signup Page 2](./assests/img/signup-page-2.png)
  ![Signup Page 3](./assests/img/signup-page-3.png)

- **Email Verification Form:** This form verifies if the provided email belongs to the student, ensuring the authenticity of the registration.

  ![Email Verification Form](./assests/img/email-verification.png)

- **Verification Code Form:** Used to validate the OTP (One-Time Password) sent to the student's email, confirming their identity.

  ![Verification Code Form](./assests/img/code-verification.png)

- **Success Page:** Displays a message confirming that the account has been successfully created.

  ![Success Page](./assests/img/signup-successful.png)

### Account Recovery System
- **Account Recovery Form:** Allows students to initiate the process of recovering their accounts in case they forget their password.

  ![Account Recovery Form](./assests/img/forgot-password.png)

- **Reset Password Form:** An interface where students can set a new password after recovering their account.

  ![Reset Password Form](./assests/img/reset-password.png)

### Student Dashboard
- **Edit Profile:** The student panel where users can update personal information and adjust account settings.

  ![Edit Profile](./assests/img/dashboard-profile.png)

- **Edit Image:** A modal that allows students to update their profile picture.

  ![Edit Image](./assests/img/dashboard-edit-image.png)

- **Payments Dashboard:** A dedicated area for students to make their tuition payments quickly and securely.

  ![Payments Dashboard](./assests/img/dashboard-payments.png)

- **Payments Table:** Displays a history of the payments made by the student, allowing them to track their financial activities.

  ![Payments Table](./assests/img/dashboard-payments-table.png)

### Admin Dashboard
- **Admin Dashboard:** A comprehensive panel that provides analytics and metrics for managing the institution.

  ![Admin Dashboard](./assests/img/dashboard-admin.png)
  ![Admin Dashboard 2](./assests/img/dashboard-admin-2.png)

- **Course Management:** A tool for the admin to add, edit, or remove courses offered by the institution.

  ![Course Management](./assests/img/dashboard-admin-courses.png)

- **Student Management:** An interface that allows the admin to view and manage student information.

  ![Student Management](./assests/img/dashboard-admin-students.png)

- **Admin Management:** Allows the admin to add or remove other administrators from the system.

  ![Admin Management](./assests/img/dashboard-admins.png)

### 404 Error
- **Page Not Found:** A custom 404 error page that displays a helpful message, guiding users back to accessible areas of the site.
- 
  ![Page Not Found](./assests/img/page-not-found.png)

## Technologies

- **Front-end:**
  - HTML5
  - CSS3
  - JavaScript
  - jQuery (AJAX)

<div style="display:flex; align-items:center; gap:12px;"> 
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery">
</div>

- **Back-end:**
  - PHP
  - SQL
  - MySQL

<div style="display:flex; align-items:center; gap:12px;"> 
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
</div>

- **Others:**
  - **.htaccess:** Configuration file for managing friendly URLs.
  - **Composer:** A tool for managing project dependencies.
  - **PHPMailer:** Used for sending automated emails.
  - **League/Plates:** Utilized for creating the templating system.
