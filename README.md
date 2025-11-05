# HUB CTC Dev Challenge
**Project Title:**  The Subjects App  

---

## Context

CTC requires a functional prototype to manage clinical subjects and their associated centers.  
The platform must provide a secure and structured way to view, create, and manage subjects linked to cancer centers.

You are asked to deliver a complete and operational solution.

---

## Technical Scope

The solution must include:

- A backend using NestJS (Node.js 24+)
- A frontend using Angular 20+
- A PostgreSQL 18+ database

All components must be installable and runnable locally in Docker.
TypeScript is required.

---

## Functional Scope

### Part 1 – Subjects

Implement a backend and frontend allowing users to display a list of subjects.  
Each subject must have at least:
- an identifier
- a number
- a name
- a birth date

The frontend must retrieve data from the backend; no mock or static data is accepted.  
Data must persist in the database.

---

### Part 2 – Subject Management

Extend the application to allow creation, modification, and deletion of subjects.  
Newly entered subjects must be stored in the database and appear in the list.  
Data integrity must be preserved at all times.

---

### Part 3 – Centers

Each subject belongs to a Center.  
Add a data model for centers.  
Centers must include both fixed attributes and variable information.  
The relationship between subjects and centers must be fully managed by the system.

---

### Part 4 – Authentication and Access Control

Add authentication to protect the application.  
Unauthenticated users may only access the login interface.  
Authenticated users can access the sites (and subjects) they are linked to.

---

### Part 5 – Audit and Data Handling

The platform must retain a trace of operations performed on subjects.  
It must also provide a way to handle sensitive information appropriately.

---

### Part 6 – Delivery and Operation

Provide the complete source code and setup instructions.  
A minimal test or verification procedure must be included. 
All changes should be versioned.

The HUB CTC Dev Team.

