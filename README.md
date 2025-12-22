# 🚗 Uber System - SRS

A **Software Engineering practical project** that models a Transportation Booking System similar to ride-hailing applications.  
The project focuses on **software analysis and design**, including UML diagrams such as **Use Case, Activity, Sequence, Class, and DFD diagrams**.

---

## 📌 Project Overview

The **Uber Booking System** is a mobile and web-based system that connects customers with nearby drivers to request, book, track, and pay for rides.  
The system supports three main actors:

- **Customer**
- **Driver**
- **Admin**

This repository contains **design-level artifacts only** (no implementation code), prepared as part of the **Software Engineering 1** course.

---

## 🎯 Objectives

- Apply **Software Engineering concepts** in a real-world system
- Practice **UML modeling**
- Define clear **functional and non-functional requirements**
- Design system workflows and data flow clearly

---

## 👥 Stakeholders

- **Customer**: Requests and tracks rides, pays, submits reviews or complaints
- **Driver**: Accepts or rejects ride requests, updates trip status
- **Admin**: Manages users, verifies drivers, handles complaints, generates reports
- **Payment Gateway**: Handles secure online payments

---

## 🗂️ Project Contents

This repository includes the following diagrams (created using **draw.io**):

### 🔹 UML & Analysis Diagrams

- **Use Case Diagram**
  - `Use case diagram.drawio.pdf`

- **Class Diagram**
  - `classDiagram.drawio.pdf`

- **Activity Diagrams**
  - `Activity & sequence --- Login.drawio.pdf`
  - `Activity & sequence --- Register.drawio.pdf`
  - `Activity --- Customer's request booking and ...`

- **Sequence Diagrams**
  - `Sequence --- Customer's request booking ...`

- **Data Flow Diagrams (DFD)**
  - `DFD --- DFD Level 0 & 1.drawio.pdf`

---

## 🔁 System Workflow (High-Level)

1. Customer registers or logs in
2. Customer requests a ride (pickup & destination)
3. System finds nearest available drivers
4. Driver accepts or rejects the request
5. Customer tracks the trip in real-time
6. Customer pays (cash or online)
7. Customer and driver can submit reviews or complaints
8. Admin manages users, complaints, and reports

---

## ⚙️ Functional Requirements (Summary)

### Customer
- Register & login
- Request and book rides
- Track trip status
- Pay via cash or online payment
- Submit reviews and complaints

### Driver
- Login with verified account
- Accept or reject ride requests
- Update trip status
- Review customers

### Admin
- Verify and manage drivers
- Manage users
- Handle complaints
- Generate and download reports

---

## 🔐 Non-Functional Requirements (Summary)

- **Performance**: Fast response time
- **Availability**: ≥ 99% uptime
- **Security**:
  - Secure authentication
  - HTTPS communication
  - Location privacy
- **Usability**: Simple and user-friendly UI/UX
- **Architecture**: MVC-based design
- **Standards**: UML-compliant diagrams

---

## 🛠️ Tools Used

- **draw.io** – UML and system diagrams
- **PDF format** – Documentation export
  
---

## 📄 Notes

- This project focuses on **analysis and design**, not implementation.
- All diagrams follow **UML standards**.
- Suitable for academic evaluation and documentation reference.

---

✅ *Feel free to extend this project later with implementation (Backend / Mobile / Web).*  
