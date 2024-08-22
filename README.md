Railway Reservation System using PL/SQL

This project is a comprehensive railway reservation system developed using PL/SQL, designed to manage the booking and management of train tickets efficiently. The system encompasses several key functionalities:

Database Structure:

Tables: The database includes tables for storing details about trains, stations, passengers, bookings, and ticket pricing.
Relations: Foreign key relationships link trains to stations, bookings to passengers, and pricing to ticket types, ensuring data integrity and consistency.
Core Features:

Booking Tickets: Users can book tickets by specifying the train, class, and journey date. The system checks seat availability and automatically updates the seat inventory.
Cancellation: The system allows users to cancel tickets, updating seat availability and processing refunds as per cancellation rules.
Waitlist Management: If a train is fully booked, the system manages a waitlist, automatically confirming tickets when seats become available.
Reporting: The system generates reports, including booking history, cancellation statistics, and revenue analysis, all processed using PL/SQL queries.
PL/SQL Procedures and Triggers:

Procedures: Various PL/SQL stored procedures handle booking, cancellation, and waitlist operations, ensuring efficient processing and error handling.
Triggers: Database triggers are implemented to enforce business rules, such as automatic waitlist confirmation and fare calculation.
Security: The system uses PL/SQL packages to encapsulate business logic, ensuring secure and modular code. User roles and privileges are managed to protect sensitive information.

This project demonstrates the power of PL/SQL in developing a robust and reliable railway reservation system, with a focus on efficiency, accuracy, and scalability.






