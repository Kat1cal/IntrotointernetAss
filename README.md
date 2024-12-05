# Zenith Health Clinic Booking System

The Zenith Health Clinic Booking System is a user-centered website designed to streamline the process of booking and managing clinic appointments. It includes features for patients, doctors, and clinic admins, ensuring efficient scheduling and appointment handling.

## Features

### Patient Features
- **Login/Signup**: Secure authentication system for patients.
- **Booking Process**:
  - Select preferred date, time, and doctor.
  - View available and booked slots.
  - Receive appointment confirmation via email.
- **Forgot Password**: Reset password functionality.

### Admin Features
- **Admin Login**: Secure authentication for administrators.
- **Dashboard**:
  - View, confirm, or cancel appointments with confirmation pop-ups.
  - Send appointment reminders via email.

### Doctor Features
- **Doctor Login**: Secure authentication for doctors.
- **Work Schedule**:
  - View assigned timetable.
  - Cancel appointments with feedback messages.

## Directory Structure

- **PHP Scripts**:
  - `admin.php`, `adminlogin.php`: Admin dashboard and login.
  - `appointment.php`, `book_doctor.php`: Booking management.
  - `cancel_appointment.php`, `confirm_booking.php`: Appointment handling.
  - `doctorlogin.php`, `doctor_home.php`, `doctor_schedule.php`: Doctor functionalities.
  - `login.php`, `register.php`, `logout.php`: User authentication.
  - `reset_password.php`, `forgot.html`: Password management.

- **Frontend Assets**:
  - `css/`: Stylesheets for the application.
  - `img/`: Images used in the UI.
  - `javascript/`: Client-side scripts for interactivity.

- **Email Handling**:
  - `PHPMailer/`: Library for sending emails (e.g., appointment confirmations, reminders).

## Installation and Setup

1. **Prerequisites**:
   - PHP 7.x or higher.
   - MySQL database.
   - A web server (e.g., Apache, Nginx).

2. **Database Setup**:
   - Predefined MySQL database schema (clinic_db.sql)
   - import the provided SQL schema.

4. **Configuration**:
   - Update database connection settings in the appropriate PHP files.

5. **Deploy**:
   - Place the files in the web server's root directory.
   - Ensure the server has write permissions for necessary directories.

6. **Access**:
   - Open the application in a web browser and follow the interface.

## Usage

- **Patients**: Login, book appointments.
- **Admins**: Oversee and manage all appointments and communications.
- **Doctors**: View and cancel their schedule and patient appointments.

## Contributing

Contributions to improve the application are welcome. Please fork the repository, make changes, and submit a pull request.

## License
