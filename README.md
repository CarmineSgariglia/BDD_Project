# Airport Management Database System
![Type](https://img.shields.io/badge/type-University%20Project-orange)

University group project developed for the **Databases (Basi di Dati)** course  
B.Sc. in Computer Science — University of Naples Federico II (A.Y. 2024/2025)

This repository contains the design and implementation of a **relational database system**
supporting core airport operations such as flight management, bookings, baggage tracking,
and access control.

The project focuses on **data modeling, integrity constraints, and database-side business logic**
using PostgreSQL.

---

## Project Overview

The system models the operational workflow of an airport, supporting both
**administrative users** and **passengers**.

Key goals of the project include:
- rigorous conceptual and logical data modeling
- strong enforcement of business rules at the database level
- consistency and correctness under concurrent operations

The database schema and logic were designed following a structured, academic methodology
(UML → relational model → physical implementation).

---

## Core Features

- **Flight management**
  - creation and scheduling of flights
  - gate assignment with temporal constraints
  - real-time flight status tracking

- **Booking system**
  - passenger reservations with seat assignment
  - prevention of invalid or conflicting bookings
  - automatic update of occupied seats

- **Baggage tracking**
  - lifecycle management (loaded, retrievable, lost)
  - constraints enforced through triggers

- **Role-based access control**
  - separation between administrative and generic users
  - privileged operations enforced via stored procedures

---

## Technical Highlights

- **PostgreSQL** as DBMS
- **UML class diagrams** for conceptual modeling
- Extensive use of:
  - CHECK constraints
  - ENUM types
  - UNIQUE indexes
  - triggers and PL/pgSQL functions
- Business rules enforced **inside the database**, not at application level

---

## Project Structure

- SQL schema definition
- Triggers and stored procedures for:
  - booking validation
  - state transitions
  - consistency enforcement
- UML diagrams (conceptual and logical design)
- Full academic documentation (in Italian)

---

## Documentation

The complete technical documentation (≈30 pages) is written in **Italian**, as required by the course, and includes:
- conceptual design (UML)
- logical schema
- physical design
- constraints, triggers, and stored procedures

📄 See: `BDD_Documentation.pdf`

---

## Academic Context

- **Course**: Databases (Basi di Dati)
- **Degree**: B.Sc. in Computer Science
- **University**: University of Naples Federico II
- **Project type**: Group coursework

---

## Contributors

- Carmine Sgariglia  
- Mattia Lemma  
- Massimo Russo  

Each team member contributed to multiple aspects of the project;  
