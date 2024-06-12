# Hospital-Management-System-JDBC
Hospital Management System
Welcome to the Hospital Management System ! This simple project is built using Java and JDBC to manage hospital operations effectively in IntelliJ Idea

This Hospital Management System includes functionalities to manage patients, doctors, and appointments, along with checking doctor availability.

Project Structure

Patient Class:
addPatient(): Add a new patient to the system.
viewPatients(): View all patients in the system.
getPatientById(): Check patient details by ID.

Doctor Class:
viewDoctors(): View all doctors in the system.
getDoctorById(): Check doctor details by ID.

Hospital Management System Class:

Driver Class: The main class that runs all the classes.
Main Menu: Provides a user interface to navigate through the system.
Exit Class: Handles the termination of the application.



Database Connection: Manages the connection to the MySQL database.
 
Patient Table: id, name, age, gender
Doctor Table: id, name, specialization
Appointments Table: patient_id, doctor_id, appointment_date
