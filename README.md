# AirZambia.com Flight Booking System

 📌 Project Overview

The **AirZambia.com Flight Booking System** is a web-based platform developed as a demonstration of full-stack web application capabilities. The system is being built by a prospective employee of **YUAI Soft Solution** to showcase practical skills in backend and frontend development using modern technologies.

The platform aims to provide a **streamlined, secure, and real-time flight booking experience**, incorporating core airline reservation concepts such as user approval workflows, flight search and booking, booking reference generation (PNR), and real-time flight status updates.

This project is intended for **academic, demonstration, and evaluation purposes only** and does not integrate with real-world airline reservation systems or payment gateways.


 🎯 Core Features

* User registration with **admin approval workflow**
* Secure user authentication and authorisation
* Flight search and booking functionality
* Automatic booking reference (PNR) generation
* Real-time flight status updates
* Role-based access control (Admin and User)
* Secure handling of user data


 🧰 Technology Stack

 Backend

* Django
* Django Rest Framework (DRF)
* RESTful API architecture
* JWT-based authentication

 Frontend

* React
* Component-based UI architecture
* API integration with backend services

 Database

* Relational database (SQLite / PostgreSQL)

👥 User Roles

 User

* Register an account
* Await admin approval
* Log in after approval
* Search for available flights
* Book flights
* View booking details using PNR
* Check real-time flight status

 Admin

* Review and approve or reject user registrations
* Manage flight information
* Manage bookings
* Update flight status information

 🔐 Security Considerations

* JWT (JSON Web Token) is used for secure and stateless authentication
* Role-based access control ensures restricted access to system features
* Sensitive user data is securely stored and accessed
* HTTPS is assumed for secure communication

 ⚖️ Legal and Compliance Notes

* The system is **aligned with general GDPR data protection principles**, including data minimization and secure handling of personal information
* The system **does not process online payments** and therefore is **not subject to PCI DSS compliance**
* No integration with external airline systems, payment gateways, or aviation data providers is included

 📊 System Design Artefacts

The project documentation includes:

* Software Requirements Specification (SRS)
* Use Case Diagram
* Data Flow Diagrams (Level 0 and Level 1)
* Entity-Relationship (ER) Diagram (optional)

These artefacts are used to guide system design, development, and evaluation.

 🚫 Out of Scope

The following features are intentionally excluded:

* Online payment processing
* Integration with real airline reservation systems (e.g., Amadeus, Sabre)
* Third-party aviation data providers (e.g., AirLabs, OpenSky Network)
* Mobile application development
* Loyalty programs or advanced analytics

 🚀 Getting Started (Development Setup)

```bash
# Clone the repository
git clone https://github.com/MishFr/airzambia-flight-booking.git

# Backend setup
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

# Frontend setup
cd frontend
npm install
npm start
```



 📌 Purpose of the Project

This project serves as:

* A technical demonstration of full-stack development skills
* A learning platform for understanding flight booking systems
* A reference system for stakeholders, developers, and testers


 🧑‍💻 Author

Frank Mischek
Prospective Employee – YUAI Soft Solution

 📄 License

This project is developed for educational and demonstration purposes only. Commercial use is not permitted.
﻿ AirZambia.com-docs


