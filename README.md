Container Yard Management System

A web-based container yard management platform developed during a software development internship at Hovmark Data ApS (Esbjerg, Denmark).

The system was designed to support daily port operations through role-based workflows for clients, drivers, and administrators, covering the complete lifecycle of container visits from order creation to billing.

Project Overview

The platform provides a centralized solution for managing container yard operations, including:

* Container visit and order registration
* Arrival and departure tracking
* Yard slot assignment
* Operational task management
* Customer visibility into container status
* Billing and tariff management
* User and client administration

The project was developed as a final internship and examination project for the AP Computer Science program.

Key Features

Client Portal

* Create and manage container orders
* View planned and actual container visits
* Track order status in real time
* Access billing records and invoices

Driver Portal

* View planned arrivals
* Activate container arrivals
* Assign yard slots manually or automatically
* Execute operational tasks
* Manage container movements inside the yard

Admin Portal

* Manage users and clients
* Create and manage orders
* Create operational tasks
* Configure yard structure
* Manage tariffs and billing
* Monitor all active and completed operations

Yard Management Logic

The system includes a structured yard model consisting of:

* Sectors
* Rows
* Slots

The assignment engine supports:

* Automatic slot allocation
* Manual assignment with recommendations
* Power-enabled container positions
* Capacity constraints
* Operational efficiency scoring
* Explainable recommendations

More than 3,000 yard positions were generated and used for testing operational workflows.

Technology Stack

Frontend

* Blazor WebAssembly

Backend

* ASP.NET Minimal API
* JWT Authentication
* Role-Based Authorization

Database

* SQL Database

Deployment

* Webmin-managed Linux environment

Architecture

The solution follows a three-layer architecture:

User → Blazor Frontend → ASP.NET API → SQL Database

Authentication is handled through JWT tokens and role-based access control.

Screenshots

Project screenshots demonstrating client, driver, and administrator workflows are available in the repository.

Business Value

The system replaces manual and legacy workflows with a dedicated operational platform tailored for container yard management.

Key benefits include:

* Improved operational visibility
* Consistent state management
* Reduced manual coordination
* Structured yard allocation
* Centralized billing management
* Role-based access control

Project Context

Company: Hovmark Data ApS
Location: Esbjerg, Denmark
Project Type: Internship & Final Examination Project
Period: October 2025 – January 2026

Future Improvements

Potential future enhancements include:

* Interactive yard map visualization
* Camera-based container recognition
* Offline/mobile-first support
* Advanced operational analytics
* Additional automation for yard planning

⸻

This repository contains project documentation, screenshots, and case study materials demonstrating the design, implementation, and deployment of the Container Yard Management System.
