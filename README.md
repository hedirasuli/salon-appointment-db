# Salon Appointment Scheduler

This is a database-driven salon appointment scheduling system built as part of the freeCodeCamp Relational Database Certification. The project uses a PostgreSQL database and a Bash script to manage services, customers, and appointments.

## 🛠 Technologies Used
- PostgreSQL: For database management.
- Bash Scripting: To create the interactive command-line interface.
- SQL: To perform CRUD operations.

## 📋 Features
- Displays a list of available services (Cut, Color, Perm).
- Allows users to book appointments by providing their phone number.
- Automatically detects new customers and asks for their name.
- Stores appointment details (customer, service, and time) in the database.

## 🚀 How to Run
To run this project, follow these steps in your terminal:

1. Rebuild the database using the provided SQL file:
   ```bash
   psql -U postgres < salon.sql
    ```
2. Give execution permission to the script:
   ```bash
   chmod +x salon.sh
    ```
3. Run the script:
   ```bash
   ./salon.sh
    ```
## 🗃 Database Schema
The project consists of three tables:
- services: Stores service names and IDs.
- customers: Stores customer names and phone numbers.
- appointments: Links customers and services with a specific time.
