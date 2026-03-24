# 🔐 Secure Inventory Management System

This repository contains a secure Inventory Management System (IMS) project developed using a **security-by-design** approach.

---

## 📄 Overview

The system was designed for a university library environment to support secure inventory, reservation, and loan management without compromising data integrity or access control.

---

## 🏗️ Architecture

The IMS follows a **three-tier architecture**:

- **Presentation Layer** — role-based dashboards and user interaction
- **Logic Layer** — authentication, validation, routing, and security middleware
- **Persistence Layer** — database operations, transaction management, and audit storage

---

## 🔐 Security Features

- STRIDE-informed threat modelling  
- Trust boundary analysis  
- Role-Based Access Control (RBAC)  
- JWT authentication and session expiry  
- Rate limiting for brute-force protection  
- Schema-based input validation  
- Audit logging for key actions  

---

## 🧠 Security Principles Applied

- Least Privilege  
- Secure Defaults  
- Defence in Depth  

---

## ⚙️ Core Functionality

- Book search and filtering  
- Loan reservation and approval workflow  
- Inventory status updates  
- Role-based access for students, librarians, and admins  
- Audit trail visibility for administrative monitoring  

---

## 🧪 Testing

The project includes both **functional** and **security** testing, including:

- reservation validation  
- duplicate request prevention  
- unauthenticated access blocking  
- session timeout handling  
- failed login rate limiting  

---

## 🧰 Key Concepts Covered

- Secure software engineering  
- Threat modelling  
- Input validation  
- Authentication and access control  
- Inventory workflow security  
- Auditability and accountability  

---

## 📎 Notes

This project demonstrates how secure software engineering principles can be embedded into system architecture and application workflows from the design stage onward.
