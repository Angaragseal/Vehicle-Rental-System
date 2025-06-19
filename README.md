# Vehicle Rental System - Database Documentation

## Overview
This project implements a relational database system using MySQL for managing a vehicle rental business. It covers vehicle inventory, customer data, booking management, damage tracking, payments, and pricing.

## Schema Design

- **branch**: Stores locations of different rental branches.
- **vehicle_type**: Defines types of vehicles (Car, Bike, SUV, etc.).
- **vehicle**: Details of each vehicle including make, model, status, and branch location.
- **customer**: Customer details and identification proofs.
- **booking**: Records vehicle rentals by customers with status tracking.
- **damage_report**: Logs reported damages on vehicles, their severity, and resolution status.
- **pricing**: Stores rental rates per vehicle type, including daily/hourly and late fees.
- **payment**: Tracks payments made against bookings, with method and status.

## Assumptions

- A vehicle belongs to one branch at a time.
- Bookings cannot overlap for the same vehicle (enforced logically in app layer).
- Damage reports can exist independently and are linked to vehicles.
- Payment status and methods are standardized using ENUM.
- Pricing is fixed per vehicle type.

## Instructions for Running

1. Use MySQL 5.7 or later.
2. Run the DDL script to create tables.
3. Run the DML script to insert sample data.
4. Execute the SQL queries to test operations and reports.
5. Extend with further queries or constraints as needed.

---
-Angarag Seal
-angaragseal55@gmail.com
