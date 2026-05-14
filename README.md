# 🔐 Streeling University Library IMS

A secure, role-based Inventory Management System (IMS) developed for a university library environment using a security-by-design approach. The system supports inventory tracking, loan management, procurement workflows, and administrative auditing while enforcing strong authentication and access control mechanisms.

---

# 📄 Overview

The application was designed to demonstrate practical secure software engineering concepts integrated throughout the software development lifecycle (SDLC).

The system supports three user roles:

* **Students** — browse inventory, reserve and renew books
* **Librarians** — manage reservations, loans, and returns
* **Administrators** — manage users, suppliers, inventory, and audit activity

---

# 🏗️ Architecture

The IMS follows a layered architecture:

* **Frontend:** React + Vite + Tailwind CSS
* **Backend:** FastAPI + SQLAlchemy
* **Database:** SQLite

---

# 🛡️ Security Features

* Role-Based Access Control (RBAC)
* JWT authentication and session expiry
* bcrypt password hashing
* Rate limiting on login endpoints
* Pydantic schema validation
* Audit logging
* Security headers and Content Security Policy (CSP)
* ORM-based database queries to reduce SQL injection risk

---

# ⚙️ Core Features

* Inventory and stock management
* Book reservation and loan workflows
* Procurement and supplier management
* Audit log monitoring
* Role-based dashboards and permissions

---

# 🚀 Running the Project

The project requires both the backend and frontend to run simultaneously.

## Backend

```bash
cd backend
.\venv\Scripts\Activate
uvicorn main:app --reload
```

Backend URL:

```text
http://127.0.0.1:8000
```

---

## Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend URL:

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

# 📌 Notes

This repository was developed as part of a secure software engineering project and later extended to support DevSecOps security testing and CI/CD automation workflows.
