# Dentist Appointment System - Formal Modelling 

## Overview
This project involves the formal modelling of a Dentist Appointment System as part of the COMP1216 Software Modelling and Design module for the 2023-24 academic year. 
The focus is on developing Event-B models using the Rodin Platform to capture the system's functionality, such as user roles, appointments, and interactions.
The coursework is a group assignment


## System Outline
The system models a **Dentist Appointment System** and is intended to manage users, appointments, and other interactions.

### Key Features
- **Users**: The system supports different user roles:
  - **Administrators**: Responsible for managing the system, including adding dentists and managing appointments.
  - **Dentists**: Perform treatments and manage appointment status.
  - **Patients**: Register to the system and book appointments.

- **Appointments**:
  - Patients can book, cancel, or rebook appointments with qualified dentists.
  - Appointments can have various states: booked, checked-in, cancelled, missed, and completed.

- **Operations**:
  - Users can log in, log out, and manage their accounts.
  - Administrators and dentists can view patient appointment records.
  - Patients can check their appointments or view their treatment history.

## Requirements Summary

### User Management
- **Login System**: Users must log in with a correct password and can log out once logged in.
- **User Roles**: Each user has one of the following roles: administrator, dentist, or patient.
- **Registration**:
  - Patients can directly register using a unique NHS number.
  - Administrators can register new administrators or dentists.

### Appointments
- **Booking**: Patients can book an appointment with a qualified dentist for a future date.
- **Restrictions**:
  - No duplicate appointments for the same treatment.
  - No appointments allowed within 14 days of receiving the same treatment.
- **States**:
  - Appointment states include: booked, checked-in, cancelled, missed, and completed.
  - Administrators must mark overdue appointments as "missed".

### Querying Operations
- **Appointment Records**:
  - Administrators or dentists can view patient appointments using their NHS number.
  - Patients can view booked appointments and treatment history.

## Tasks

### Task 1: Class Diagram (5 marks)
Identify the main entities from the system requirements and create a UML class diagram representing the relationships between these entities.

### Task 2: Event-B Model (45 marks)
Develop an Event-B model of the system based on the requirements:
- **Entities**: Define Event-B sets, constants, variables, and invariants.
- **Events**: Model key events such as user registration, appointment booking, and treatment completion.
- **Constraints**: Specify constraints between variables using invariants.

#### Required Events
- Administrator registration
- Dentist registration
- Patient registration
- User login and logout
- Appointment booking, cancellation, and rebooking
- Treatment completion and overdue appointment handling
- Viewing patient records

**Note**: Use extension refinement to structure the Event-B model for extra marks.

## Technologies Used
- **Event-B**: Formal modelling method used to specify and design the system.
- **Rodin Platform**: A tool for creating and verifying Event-B models.

## Acknowledgments
- **Module Leads**:
  - Mohammad Soorati - [M.Soorati@soton.ac.uk](mailto:M.Soorati@soton.ac.uk)
  - Thai Son Hoang - [T.S.Hoang@soton.ac.uk](mailto:T.S.Hoang@soton.ac.uk)
  - Luis-Daniel Ibanez - [L.D.Ibanez@soton.ac.uk](mailto:L.D.Ibanez@soton.ac.uk)

## Contact
For any queries or feedback regarding the coursework, please contact the module leads via the provided email addresses.

