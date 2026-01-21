# Campus Events – Web Based Campus Event Management System

Campus Events is a web-based campus event management system developed to manage academic, social, and cultural events within a university.

## Project Overview
The system enables users to view, create, manage, and participate in campus events through a centralized web platform. It supports multiple user roles with different authorization levels and ensures data consistency through database-level business logic.

## User Roles
- Student: View events, register/cancel participation, submit feedback
- Organizer: Create and manage events, view participants and feedback
- Admin: Manage users, assign organizers, monitor system activity and logs

## Features
- Role-based authentication and authorization
- Event creation, categorization, and management
- Event participation with capacity control
- Feedback and rating system
- Notification and system logging mechanism
- Secure authentication with encrypted passwords
- Transaction management for critical operations

## Database & Backend Logic
- Relational database design with normalized tables
- Many-to-many relationships for event participation
- Stored procedures for optimized querying
- Triggers for:
  - Automatic capacity updates
  - Notification creation
  - System activity logging
- SQL injection prevention using prepared statements

## Technologies Used
- Frontend: HTML, CSS, JavaScript
- Backend: PHP
- Database: MySQL
- SQL Features: Triggers, Stored Procedures, Transactions

## Notes
This project was developed as part of a university database management course and represents a complete, functional web application rather than a standalone database design.
