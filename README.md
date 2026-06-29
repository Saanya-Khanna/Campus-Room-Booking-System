# Campus Room Booking System

## Overview
The Campus Room Booking System is a conceptual project designed to model how students and staff can reserve rooms within a campus environment. This project focuses on system design and workflow representation through UML diagrams, specifically an Activity Diagram and a Data Access & Manipulation (DAM) Diagram.

The goal of this project is to demonstrate understanding of system processes, data flow, and interactions between users and the system.

## Features (Conceptual)
- User login and authentication
- Search available rooms by date, time, and building
- Room selection and booking submission
- Conflict detection for overlapping bookings
- Booking confirmation workflow

## Project Scope
This project was completed as part of a class assignment and focuses on:
- System design and modeling
- Logical flow of application processes
- Data structure and interaction design

Note: This repository does not include implementation code. It is focused on system design only.

## Diagrams

### 1. Activity Diagram
The Activity Diagram represents the step-by-step workflow of the room booking process.

**Key flow:**
1. User logs into the system
2. System validates credentials
3. User enters booking details (date, time, location)
4. System retrieves available rooms
5. User selects a room and submits booking
6. System checks for conflicts:
   - If conflict exists → user is prompted to select another time
   - If no conflict → booking is confirmed
7. Confirmation is sent to the user

### 2. Data Access & Manipulation (DAM) Diagram
The DAM Diagram illustrates how data is structured and how different entities interact within the system.

**Includes:**
- User entities
- Room and availability data
- Booking/reservation records
- Relationships between users, rooms, and bookings

This diagram helps visualize how data flows and is managed within the system.

## Tools Used
- Miro
- GitHub for version control and documentation
