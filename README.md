# Spa-Booking-System - DBMS 1 and SIA Final Project 

A spa booking database and web system with customers, therapists, services, rooms, bookings, payments, and automatic scheduling with conflict detection, waitlists, and audit logs.

Track: Merged Track. DBMS 1 and SIA are one combined system with one defense. Group size: 6 members.

## Group roster and ownership matrix

| Member | GitHub username | Tables | Complete resource | Join report and type | Feature role |
|---|---|---|---|---|---|
| A - Joanna Joyce Caromayan | Joyce Moycee05 | roles, users, customers | Users | R1 Users with their roles (INNER JOIN) | Core |
| B - Sigrid Althia Delvo | Silthia | service_categories, services, rooms | Services | R2 Services never booked (LEFT JOIN) | Master data |
| C - Mary Aljane Cadano | marie-chan | bookings, booking_services, payments | Bookings | R3 Booking details with customer and therapist (INNER JOIN) | Transactions |
| D - Mary Aljane Cadano | camy_ky | therapists, therapist_schedules, therapist_time_off | Therapists | R4 Therapists vs bookings (FULL OUTER JOIN via UNION) | Unique feature (rules) |
| E - Jerry Mae Callao | jerrydevvv | booking_status_history, activity_logs, notifications, waitlist_entries | Waitlist | R5 Bookings with no reminder (LEFT JOIN) | Unique feature (workflow, alerts), Audit |
| F - Josh Daligdig | jadaligdig | promotions, reviews | Promotions | R6 Revenue by service category (INNER JOIN) | Reports ||
