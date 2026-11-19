# Real Estate Management System (REMS)

**DIGT3101 – Project Deliverable 1**  
**Team 5 | York University, Lassonde School of Engineering**

## Project Overview

The Real Estate Management System (REMS) is a web-based application designed to centralize property listing management and simplify interactions between prospective tenants or buyers, real estate agents/property managers, and system administrators.

REMS aims to provide a single platform where users can browse available properties, manage listings, submit inquiries or applications, and access relevant property information.

The project is being developed as part of DIGT3101 using an Agile development approach.

## Project Objectives

The primary objectives of REMS are to:

- Centralize property listings and related information.
- Provide secure user authentication and role-based access.
- Allow authorized agents and property managers to create, edit, and remove listings.
- Enable users to browse, search, and filter available properties.
- Support property inquiries and applications.
- Provide administrative account management functionality.
- Maintain reliable data storage and a user-friendly interface.

## Planned Features

| Feature | Description |
|---|---|
| User Authentication | Account registration, login, logout, and role-based access |
| Property Management | Create, edit, and remove property listings |
| Property Search | Browse and filter properties by location, price, type, and availability |
| Inquiries & Applications | Submit and review property inquiries or applications |
| Property Status | Manage available, pending, rented, and sold statuses |
| User Administration | Manage registered accounts and access permissions |
| Submission History | Allow users to review previous inquiries and applications |

These features represent the planned project scope and will be implemented incrementally.

## Technology Stack

| Component | Technology |
|---|---|
| Frontend | React |
| Backend | Rust |
| Database | MySQL or PostgreSQL (to be finalized) |
| Version Control | Git and GitHub |
| Project Management | GitHub Projects |
| Testing | Rust built-in testing framework (`cargo test`), integration testing, and acceptance testing |

Specific libraries, frameworks, and database technologies will be finalized during the system design phase.

## Development Methodology

REMS follows an Agile development approach using two-week sprints.

Development is organized into three major deliverables:

### Deliverable 1 – Requirements and Project Planning
**Due: November 21, 2026**

- Problem statement and project motivation
- Functional and nonfunctional requirements
- UML use case diagram and descriptions
- User stories and acceptance criteria
- Product backlog and sprint planning
- Testing and performance analysis plan

### Deliverable 2 – System Design
**Due: February 7, 2027**

- Software Design Document
- UML class, sequence, and activity diagrams
- Database schema and entity relationship diagram
- System architecture and technical design

### Deliverable 3 – Implementation and Testing
**Due: March 28, 2027**

- Frontend and Rust backend implementation
- Database integration
- Unit and integration testing
- Acceptance testing and defect resolution
- Final documentation and project submission

## Team Members

| Team Member | Primary Responsibility |
|---|---|
| Katherine Arnaud | Frontend Development |
| Katherine (Katie) Bauchman | Frontend Development |
| Quinn Nguyen | Backend Development |

All team members contribute to requirements analysis, planning, documentation, testing, and project reviews.

## Project Management

The team uses GitHub and GitHub Projects to organize development activities, manage backlog items, assign responsibilities, and track progress.

The product backlog is aligned with the functional requirements documented in Deliverable 1.

Development tasks and priorities will be reviewed and updated as the project progresses.

## Testing Strategy

REMS will be evaluated using multiple levels of testing:

- **Unit Testing:** Verify individual Rust backend functions and frontend components.
- **Integration Testing:** Confirm correct communication between the React frontend, Rust backend, and database.
- **Acceptance Testing:** Validate major workflows against documented user stories and acceptance criteria.
- **Performance Testing:** Evaluate system responsiveness under defined test conditions.

Test cases are mapped to functional requirements to support traceability and verify coverage.

## Project Status

**Current Phase:** Deliverable 1, Requirements and Project Planning

The project is currently focused on requirements documentation, planning, and preparation for the system design and implementation phases.

Application setup and installation instructions will be added once the project structure and remaining technology selections are finalized.

## Academic Project

This repository contains coursework developed for DIGT3101 at York University's Lassonde School of Engineering.

The system is intended as an academic software development project and is not currently designed for commercial deployment.
