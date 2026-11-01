# Spa-Booking-System - DBMS 1 and SIA Final Project 

A spa booking database and web system with customers, therapists, services, rooms, bookings, payments, and automatic scheduling with conflict detection, waitlists, and audit logs.

Track: Merged Track. DBMS 1 and SIA are one combined system with one defense. Group size: 6 members.

## Group roster and ownership matrix

| Member | GitHub username | Tables | Complete resource | Join report and type | Feature role |
|---|---|---|---|---|---|
| A - [Joanna Joyce Caromayan](https://github.com/) | Joyce Moycee05 | roles, users, customers | Users | R1 Users with roles (INNER JOIN) | Core |
| B - [Jerry Mae Callao](https://github.com/jerrydevvv) | [jerrydevvv](https://github.com/jerrydevvv) | service_categories, services, rooms | Services | R2 Unused services and rooms (LEFT JOIN) | Master data |
| C - [KC Cimafranca](https://github.com/camy_ky) | [camy_ky](https://github.com/camy_ky) | bookings, booking_services, payments | Bookings | R3 Booking details (INNER JOIN) | Transactions |
| D - [Mary Aljane Cadano](https://github.com/marie-chan) | [marie-chan](https://github.com/marie-chan) | therapists, therapist_schedules, therapist_time_off | Therapists | R4 Therapists vs bookings (FULL OUTER JOIN via UNION) | Unique feature (rules) |
| E - [Erich Cabugnason](https://github.com/erichs333) | [erichs333](https://github.com/erichs333) | booking_status_history, activity_logs, notifications, waitlist_entries | Waitlist | R5 Bookings with no reminder (LEFT JOIN) | Unique feature (workflow, alerts), Audit |
| F - Josh Daligdig | jadaligdig | promotions, reviews | Promotions | R6 Revenue by category (INNER JOIN) | Reports |
