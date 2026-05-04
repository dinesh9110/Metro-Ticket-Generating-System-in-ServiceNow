# Metro-Ticket-Generating-System-in-ServiceNow
Digitize metro ticket booking using ServiceNow for fast, accessible, and automated QR-based tickets. Users select stations and travel details, fares are calculated automatically, and tickets are generated instantly. Uses Service Catalog, Flow Designer, and Notifications for a seamless travel experience.

# 🚇 Metro Ticket Automation System (ServiceNow)

## 📌 Project Overview
This project digitizes metro ticket booking using ServiceNow by automating ticket generation, fare calculation, and QR-based access.

---

## 🎯 Objectives
- Enhance commuter convenience using digital ticketing
- Automate fare calculation
- Enable QR-based ticket validation
- Store structured data for analytics
- Promote cashless payments

---

## 🧱 Architecture

### 🔹 Tables
- Metro Station (`u_metro_station`)
- Metro Fare (`u_metro_fare`)
- Metro Database (`u_metro_database`)

### 🔹 Modules Used
- Service Catalog
- Flow Designer
- Client Scripts
- UI Policies
- Script Includes

---

## ⚙️ Features

### ✅ Ticket Booking
- Select Source & Destination
- Choose number of passengers
- Select journey type

### ✅ Dynamic Fare Calculation
- Based on station mapping
- Supports single & return journey

### ✅ QR Code Generation
- Generated dynamically after submission
- Used for ticket validation

### ✅ Data Storage
- Stores booking data in custom table

---

## 🔄 Workflow

1. User opens Service Portal
2. Selects "Book QR Ticket"
3. Enters journey details
4. Fare auto-calculated
5. Submits request
6. QR Code generated
7. Data stored in database

---

## 🧠 Automation Logic

- Client Script → Fare calculation
- Script Include → Fetch fare dynamically
- Flow Designer → Store data in table

---

## 🔐 Security

- Role-based ACLs
- Users cannot access backend tables
- Only form interaction allowed

---

## 🧪 Testing

- Form validation tested
- QR generation verified
- Data storage validated

---

## 🚀 Future Enhancements

- Payment Gateway Integration
- Email/SMS Ticket Delivery
- Real-time metro analytics dashboard

---

## 🎥 Demo
[Add your video link here]

---

## 👨‍💻 Author
Dinesh P
