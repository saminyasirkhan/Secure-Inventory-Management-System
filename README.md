# 🔐 Streeling University Library Inventory Management System (IMS)

A secure, role-based Inventory Management System developed for a university library environment using a **security-by-design** approach. The platform supports inventory tracking, loan management, procurement workflows, and administrative auditing while enforcing strong authentication and access control mechanisms.

---

# 📄 Project Overview

The system was designed to demonstrate secure software engineering principles integrated throughout the software development lifecycle (SDLC). It combines modern web technologies with layered security controls to protect sensitive operational and user data.

The application supports multiple user roles including:

* **Students** — browse inventory, reserve and renew books, manage personal loans
* **Librarians** — manage circulation workflows, approve reservations, process returns
* **Administrators** — manage users, suppliers, procurement, inventory, and audit activity

---

# 🏗️ System Architecture

The IMS follows a layered architecture consisting of:

* **Frontend Layer** — React + Vite user interface
* **Application Layer** — FastAPI backend APIs, authentication, validation, and business logic
* **Persistence Layer** — SQLite database with SQLAlchemy ORM

---

# 🛡️ Security Features

The project incorporates several security-focused controls and secure development practices:

* Role-Based Access Control (RBAC)
* JWT-based authentication and session expiry
* Password hashing using bcrypt
* Rate limiting on authentication endpoints
* Input validation using Pydantic schemas
* Audit logging for sensitive actions
* Security headers and Content Security Policy (CSP)
* ORM-based database interaction to reduce SQL injection risk
* Layered access-control enforcement across backend routes

---

# 🧠 Security Engineering Concepts

This project demonstrates practical implementation of:

* Secure Software Engineering Principles
* Defence in Depth
* Least Privilege
* Secure Defaults
* Threat Modelling
* Trust Boundary Analysis
* Authentication and Authorisation Controls
* Security Logging and Auditability

---

# ⚙️ Core Functionality

## Inventory Management

* Real-time inventory and stock tracking
* Category and availability management
* Low-stock monitoring

## Loan and Reservation Workflow

* Book reservations and approvals
* Loan renewals and returns
* Reservation conflict prevention

## Procurement Management

* Supplier management
* Procurement order tracking
* Stock acquisition workflows

## Administrative Monitoring

* Audit log visibility
* User management
* Role administration
* Operational reporting

---

# 🧪 Testing and Validation

The project includes both functional and security-focused validation, including:

* Authentication testing
* Role-access validation
* Duplicate reservation prevention
* Session expiry handling
* Input validation testing
* Rate-limiting verification
* Unauthorised access checks

---

# 🧰 Technology Stack

## Frontend

* React
* Vite
* Tailwind CSS

## Backend

* FastAPI
* SQLAlchemy
* Pydantic
* JWT Authentication

## Database

* SQLite

---

# 🚀 Running the Project

The project consists of a FastAPI backend and a React frontend. Both services must be running simultaneously.

---

## 1. Start the Backend

Open a terminal and navigate to the backend directory:

```bash
cd backend
```

Activate the virtual environment:

```bash
.\venv\Scripts\Activate
```

Start the FastAPI server:

```bash
uvicorn main:app --reload
```

Backend URL:

```text
http://127.0.0.1:8000
```

---

## 2. Start the Frontend

Open a second terminal and navigate to the frontend directory:

```bash
cd frontend
```

Install dependencies if required:

```bash
npm install
```

Run the frontend development server:

```bash
npm run dev
```

Frontend URL (default):

```text
http://localhost:5173
```

---

# 🔑 Default Test Accounts

| Role      | Username                                                        | Password   |
| --------- | --------------------------------------------------------------- | ---------- |
| Admin     | [admin@streeling.ac.uk](mailto:admin@streeling.ac.uk)           | admin123   |
| Librarian | [librarian1@streeling.ac.uk](mailto:librarian1@streeling.ac.uk) | librarian1 |
| Librarian | [librarian2@streeling.ac.uk](mailto:librarian2@streeling.ac.uk) | librarian2 |
| Student   | [student1@streeling.ac.uk](mailto:student1@streeling.ac.uk)     | student1   |
| Student   | [student2@streeling.ac.uk](mailto:student2@streeling.ac.uk)     | student2   |
| Student   | [student3@streeling.ac.uk](mailto:student3@streeling.ac.uk)     | student3   |

---

# 📌 Repository Notes

This repository was originally developed as part of a secure software engineering coursework project focused on applying security principles during system design and implementation. The project was later extended to support DevSecOps security testing and CI/CD automation workflows.

---

# 📜 License

This repository is intended for educational and demonstration purposes.
