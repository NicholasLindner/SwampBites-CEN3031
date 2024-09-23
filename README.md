# Web-based Scheduling System for SwampBites Employees

**Project Duration:** February 2024 – May 2024  
**Languages & Technologies:** Python, JavaScript, Flask, SQLite

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [System Architecture](#system-architecture)
4. [Role-Based Access](#role-based-access)
5. [Real-Time Synchronization](#real-time-synchronization)
6. [Usage](#usage)

---

## Overview
The **Web-based Scheduling System** is a web application designed to streamline staff allocation and scheduling for SwampBites employees. The system allows managers to easily assign shifts to staff, while employees can view their schedules, request time off, choose available hours, and manage their profiles. The platform supports real-time data synchronization and multi-tiered access controls, ensuring that different users (employees, managers) have appropriate permissions to interact with the system.

---

## Features
- **Staff Scheduling:** Allows managers to assign shifts and schedule employees quickly and efficiently.
- **Employee Requests:** Employees can request time off and choose their preferred hours of availability.
- **Profile Management:** Employees can maintain their own profiles, which include contact information and work preferences.
- **Responsive Front-End:** The system is designed with a mobile-friendly, dynamic front-end that adapts to different screen sizes for an optimal user experience.
- **Secure, Role-Based APIs:** RESTful APIs developed with Flask and JavaScript to handle user authentication and manage permissions based on roles (managers, employees).
- **Real-Time Data Sync:** Ensures that all users have the latest scheduling information without needing to refresh the page.
- **Scalable Design:** Supports over 10,000 users with a secure, robust database built on SQLite.

---

## System Architecture
The application follows a **client-server architecture**:

- **Back-End (Server):** Developed using **Flask** and connected to an **SQLite** database to handle user data, scheduling, and requests. RESTful APIs allow secure interactions between the front-end and back-end.
- **Front-End (Client):** Created with **HTML**, **CSS**, and **JavaScript**, providing a dynamic and responsive interface for employees and managers. 
- **Real-Time Updates:** The system supports real-time data synchronization using WebSockets or polling, ensuring that any schedule changes are immediately visible to all users.

---

## Role-Based Access
The system enforces **multi-tiered access controls**:
- **Managers:** Can assign shifts, approve/deny time-off requests, and manage staff profiles.
- **Employees:** Can view their schedules, request time off, update their availability, and manage their profiles.

Each user role has access only to the functionality relevant to their position, with APIs verifying access levels before any data is manipulated.

---

## Real-Time Synchronization
The scheduling system ensures that data is synchronized across all users in real-time. When a manager assigns a shift or approves a time-off request, the changes are instantly reflected on the employees' profiles without requiring a manual refresh.

---

## Usage
1. **Login:** Users (managers or employees) must log in with their credentials to access the scheduling system.
2. **Employee Interface:**
   - View assigned schedules.
   - Request time off.
   - Update availability.
   - Manage profile information.
3. **Manager Interface:**
   - Assign shifts to employees.
   - View and manage employee availability.
   - Approve or deny time-off requests.
4. **Real-Time Updates:** All updates are automatically reflected in the system.

---
