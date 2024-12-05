# Dorca Hospital Management System

The Dorca Hospital Management System is a comprehensive solution for managing hospital operations. It provides functionality to manage appointments, track inventory, and facilitate doctor and staff activities. The system aims to improve hospital administration and ensure a smooth experience for both patients and medical staff.

## Features

- Patient Management: 
  - Patients can book appointments with doctors.
  - Patients can view the status of their appointments (Scheduled, Completed, Cancelled).
  
- Doctor Dashboard:
  - Doctors can log in to view their upcoming appointments.
  - Doctors can update their availability.

- Appointment Management:
  - Admins can view and manage all appointments.
  - Patients and doctors can check scheduled and completed appointments.

- Inventory Management:
  - Track and manage medical supplies and equipment.
  - Admins can update inventory levels and monitor stock.

- Staff Management:
  - Admins can manage hospital staff (add, update, delete).
  - View and assign roles for various staff members (doctors, nurses, etc.).

## Technologies Used

- Frontend: Java Swing for building the user interface.
- Backend: Java with JDBC for database connectivity.
- Database: SQL Server for managing hospital data (patients, doctors, appointments, inventory, staff).
- JavaBeans: Used for managing data and business logic in the application.

## Database Setup

1. Database Connection:
   The system connects to a **SQL Server** database with the following details:
   - URL: `jdbc:sqlserver://localhost:1433;databaseName=HospitalDB;encrypt=true;trustServerCertificate=true;`
   - Username: `hunter`
   - Password: `hunter42`

2. Database Tables:
   - `patients`: Contains patient records.
   - `doctors`: Contains doctor details.
   - `staff`: Contains hospital staff records.
   - `appointments`: Stores information about patient appointments.
   - `inventory`: Stores medical inventory data.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Dorca-Hospital-Management-System.git
