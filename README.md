
# Airline Management System

## Introduction

This project is a simple Airline Management System built using NetBeans and deployed on a XAMPP server.  It provides a basic administrative interface for managing flights, passengers, and bookings. This system is designed for a single administrator to manage all aspects of the airline's operations within a limited scope.

## Installation

1. **Install XAMPP:** Download and install XAMPP from [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html).  Ensure Apache and MySQL are running.

2. **Import Database:**  The database (likely a MySQL database) is required for this project.  Import the SQL file (e.g., `airline_db.sql`) into your MySQL database using phpMyAdmin (included with XAMPP).  The exact name and location of the SQL file will depend on how the project is structured.

3. **Deploy Project:** Copy the project files from the NetBeans project directory to your XAMPP's `htdocs` directory (e.g., `C:\xampp\htdocs\airline_management`).

4. **Access the Application:** Open your web browser and navigate to `http://localhost/airline_management` (or the appropriate URL based on your directory structure).


## Usage

The application utilizes a simple login system. The default credentials are:

* **Username:** admin
* **Password:** admin

After logging in, you will be directed to the dashboard. From there, you can access the following functionalities:

* **Manage Flights:** Add, edit, and delete flight information.
* **Manage Passengers:** Add, edit, and delete passenger information.
* **Ticket Booking:** Create new ticket bookings.
* **Ticket Cancellation:** Cancel existing ticket bookings.


## Features

* **Flight Management:** Add, update,search and delete flight details (flight number, destination, departure time, etc.).
* **Passenger Management:** Add, update,search and delete passenger details (name, contact information, etc.).
* **Ticket Booking:**  Create,update and delete new bookings, associating passengers with flights.
* **Ticket Cancellation:** Cancel existing bookings.
* **Secure Login:**  Basic admin login with default credentials (for demonstration purposes).

## Contributing

Contributions are welcome! Please feel free to fork this repository and submit pull requests.  Before contributing, please review the code style and ensure your changes are well-documented.
