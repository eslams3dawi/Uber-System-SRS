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

All diagrams are located inside the **`Diagrams.pdf/`** directory and were created using **draw.io**.

---

### 📌 Use Case Diagram
- [Use case diagram (PDF)](Diagrams.pdf/Use%20case%20diagram.drawio.pdf)

---

### 📌 Class Diagram
- [Class Diagram (PDF)](Diagrams.pdf/classDigram.drawio.pdf)

---

### 📌 Activity Diagrams & Sequence Diagram

#### 🔹 Login Flow
- [Activity & Sequence – Login (PDF)](Diagrams.pdf/Activity%20%26%20sequence%20---Login.drawio.pdf)

#### 🔹 Register Flow
- [Activity & Sequence – Register (PDF)](Diagrams.pdf/Activity%20%26%20sequence%20---Register.drawio.pdf)

#### 🔹 Customer Booking & Driver Acceptance Flow
- [Activity – Customer Booking & Driver Acceptance (PDF)](Diagrams.pdf/Activity---Customer's%20request%20booking%20and%20Driver's%20acceptance%20flow.drawio.pdf)

---

### 📌 Sequence Diagram

#### 🔹 Customer Booking & Driver Acceptance
- [Sequence---Customer's request booking and Driver's acceptance flow.drawio (2))](Diagrams.pdf/Sequence---Customer's%20request%20booking%20and%20Driver's%20acceptance%20flow.drawio%20(2).pdf)

---

### 📌 Data Flow Diagrams (DFD)

#### 🔹 Level 0 & Level 1
- [DFD Level 0 & 1 (PDF)](Diagrams.pdf/DFD---DFD%20Level%200%20%26%201.drawio.pdf)

---

### 📌 Software Requirements Specification (SRS)
- [Uber Booking System – SRS (PDF)](Diagrams.pdf/Uber%20Booking%20System%20-%20SRS.pdf)

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
