# 📄 Software Requirement Specification (SRS) - Logistics Management System

## 1. Introduction

**Purpose**:  
This system is designed for small logistic businesses to manage their trips, vehicles, drivers, companies, and reports through a responsive web interface.

**Scope**:  
A browser-based logistics dashboard that does not require a backend. It provides CRUD operations, analytics, exportable reports, and PDF invoices.

## 2. Functional Requirements

- User login with role-based access (Admin/Staff)
- Dashboard with trip/vehicle/driver/revenue stats
- Trip management with filtering and PDF invoice generation
- CRUD for drivers, vehicles, and companies
- Report module with placeholder charts

## 3. Non-Functional Requirements

- Should work on all major browsers
- Must be responsive on desktop/tablet
- All data stored temporarily (no persistence)

## 4. User Roles

- **Admin**: Full access to all features
- **Staff**: Limited access (based on frontend simulation)

## 5. Technologies Used

- HTML5, CSS3, JavaScript
- Bootstrap 5
- jsPDF for PDF generation

---

📌 *This is a static front-end prototype. Can be extended to full stack if required.*
