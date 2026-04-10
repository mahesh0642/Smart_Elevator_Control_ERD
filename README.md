# Smart Elevator Control System - ER Diagram

## 📌 Overview
This project presents the database design (ER Diagram) for a Smart Elevator Control System used in large buildings like corporate towers, malls, and hospitals.

The system is designed to efficiently manage elevator operations, handle user requests, and track system performance.

---

## 🧠 Problem Statement
Modern buildings operate multiple elevators across many floors. The system must:

- Manage multiple buildings
- Handle multiple elevators per building
- Track floor-level requests
- Assign elevators efficiently
- Maintain ride history
- Monitor elevator status
- Track maintenance activities

---

## 🏗️ System Design Highlights

### 1. Core Entities
- Buildings
- Floors
- Shafts
- Elevators

### 2. Dynamic Entities
- Requests
- Ride Assignments
- Ride Logs

### 3. Support Entities
- Elevator Status (real-time tracking)
- Maintenance (history tracking)

---

## 🔗 Key Design Decisions

- **Separation of concerns**
  - Static data (e.g., buildings, elevators)
  - Dynamic data (e.g., requests, rides)

- **Many-to-Many Handling**
  - Elevator ↔ Floor handled using a junction table

- **Scalability**
  - Supports multiple buildings and high traffic

- **History Preservation**
  - Ride logs and maintenance records are stored separately

---

## 📊 Features Supported

- Track number of buildings and elevators
- Identify which elevator serves which floors
- Monitor request lifecycle (pending → assigned → completed)
- Analyze ride data for performance
- Track elevator maintenance history
- Monitor real-time elevator status

---

## 🛠️ Tools Used
- Eraser 
---

## 🙌 Feedback
Open to suggestions and improvements!
