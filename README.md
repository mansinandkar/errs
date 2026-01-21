# Emergency Resource Reservation and Coordination System (ERRS)
---

## Project Overview

The Emergency Resource Reservation and Coordination System (ERRS) is a relational database system designed to manage and coordinate critical emergency resources such as ambulances, ICU beds, ventilators, and medical staff across hospitals, NGOs, and emergency response organizations.

The system supports real-time reservation, availability tracking, and auditing of emergency resources while enforcing data integrity and preventing double-booking. This project demonstrates end-to-end database design and implementation using advanced SQL concepts.

---

## Project Objectives

- Design a normalized relational database schema
- Enforce referential integrity using primary and foreign keys
- Populate dimension and transactional tables with realistic data
- Create analytical SQL views for operational decision-making
- Implement auditing for lookup tables
- Demonstrate advanced SQL concepts:
  - Views
  - Triggers
  - Stored Procedures
  - User-Defined Functions (UDFs)
  - Cursors
- Follow SQL documentation and coding standards

---

## Database Design

The database consists of dimension tables, transactional tables, and audit tables designed using normalization principles.

### Key Entities
- Hospitals
- Organizations (NGOs, EMS, Fire Departments)
- Resource Types
- Resources
- Locations
- Staff
- Reservations (Transactional)
- ResourceAudit (Audit Table)

All tables are connected using primary and foreign keys to ensure referential integrity.

The Entity Relationship Diagram (ERD) is included in the `reports/` directory.

---

## Tools and Technologies

- Database: Microsoft SQL Server
- Query Language: T-SQL
- Development Tool: SQL Server Management Studio (SSMS)
- Modeling: ER Diagram 
- Version Control: Git and GitHub

---

## Implementation Details

- Table Creation

- Data Population

- Views and Queries

- Audit Table and Triggers

- Stored Procedure and User-Defined Function

- Cursor Implementation

---

## Contributors

- Mansi Nandkar
- Suraj Ravindra Rao


- Documentation Standards



