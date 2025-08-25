# Requirement Analysis in Software Development

This repository contains a detailed Requirement Analysis for a Booking Management System. It includes functional and non-functional requirements, key activities, a use case diagram, and acceptance criteria.

---

## Table of Contents
- [What is Requirement Analysis?](#what-is-requirement-analysis)
- [Why is Requirement Analysis Important?](#why-is-requirement-analysis-important)
- [Key Activities in Requirement Analysis](#key-activities-in-requirement-analysis)
- [Types of Requirements](#types-of-requirements)
  - [Functional Requirements](#functional-requirements)
  - [Non-functional Requirements](#non-functional-requirements)
- [Use Case Diagrams](#use-case-diagrams)
- [Acceptance Criteria](#acceptance-criteria)

---

## What is Requirement Analysis?
Requirement Analysis is the process of identifying, gathering, and documenting the needs and expectations of stakeholders for a software project.  
It ensures the development team clearly understands what needs to be built, reducing misunderstandings, scope creep, and project delays.  
Requirement Analysis is a crucial phase in the Software Development Life Cycle (SDLC) because it sets the foundation for successful software development.

---

## Why is Requirement Analysis Important?
Requirement Analysis is critical in SDLC for several reasons:

- **Clarifies Project Scope:** Ensures the development team and stakeholders agree on what the system should achieve.
- **Reduces Errors:** Detects potential issues early in the project, saving time and costs later.
- **Improves Communication:** Provides a clear documentation reference for developers, testers, and stakeholders.

---

## Key Activities in Requirement Analysis
- **Requirement Gathering:** Collecting information about what users and stakeholders need from the system.
- **Requirement Elicitation:** Refining and understanding requirements through interviews, surveys, and workshops.
- **Requirement Documentation:** Writing detailed documents including specifications, user stories, and use cases.
- **Requirement Analysis and Modeling:** Organizing requirements, prioritizing features, and creating visual models like diagrams.
- **Requirement Validation:** Reviewing requirements with stakeholders to ensure accuracy and completeness.

---

## Types of Requirements

### Functional Requirements
Functional requirements define what the system **should do**. Examples for a booking system:
- User registration and login
- Property search and filters
- Booking and reservation management
- Payment processing
- Admin managing property listings

### Non-functional Requirements
Non-functional requirements define **how the system performs**. Examples:
- **Performance:** Page load time < 2 seconds
- **Security:** Encrypt passwords and secure payments
- **Scalability:** Handle many users concurrently
- **Reliability:** System uptime ≥ 99%

---

## Use Case Diagrams
Use Case Diagrams illustrate interactions between system actors and the system itself. They provide a visual overview of system functionality and help stakeholders understand requirements clearly.

![Booking System Use Case Diagram](alx-booking-uc.png)

**Benefits:**
- Helps visualize system functionality
- Clarifies roles of different actors
- Supports communication between stakeholders and developers

---

## Acceptance Criteria
Acceptance Criteria define the conditions a feature must meet to be considered complete. They ensure developers and stakeholders have a shared understanding of when a feature is "done."

**Example (Checkout Feature):**
- User can select a property and add it to checkout.
- Payment is securely processed via the integrated payment gateway.
- Confirmation email is sent after successful booking.
- Total booking amount is correctly calculated including taxes.
- Feature can be reviewed and approved by stakeholders once criteria are met.

---

