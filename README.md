# Spa-Booking-System - DBMS 1 and SIA Final Project 

A spa booking database and web system with customers, therapists, services, rooms, bookings, payments, and automatic scheduling with conflict detection, waitlists, and audit logs.

Track: Merged Track. DBMS 1 and SIA are one combined system with one defense. Group size: 6 members.

## Group roster and ownership matrix

| Member | GitHub username | Tables | Complete resource | Join report and type | Feature role |
|---|---|---|---|---|---|
| A - [Joanna Joyce Caromayan] | [Joyce_Moycee05] | patients, appointments, medical_records | Patients | R1 Appointment schedule (INNER JOIN) | Core |
| B - [Sigrid Althia Delvo] | [Silthia] | departments, doctors, users | Doctors | R12 Accounts and linked doctor (LEFT JOIN) | Master data |
| C - [KC Cimafranca] | [camy_ky] | admissions, invoices, payments | Payments | R7 Billing summary (INNER JOIN) | Transactions |
| D - [Mary Aljane Cadano] | [marie-chan] | rooms, beds | Beds | R5 Bed board (RIGHT JOIN), R6 Departments vs rooms (FULL OUTER JOIN via UNION) | Unique feature (rules) |
| E - [Jerry Mae Callao] | [jerrydevvv] | medicines, prescriptions, audit_log | Medicines | R11 Audit trail (LEFT JOIN) | Unique feature (workflow, alerts), Audit |
| F - Josh Daligdig | jadaligdig | lab_tests, lab_orders | Lab tests | R4 Never-used lab tests (LEFT JOIN) | Reports |
