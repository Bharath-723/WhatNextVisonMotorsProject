# 🚗 WhatNext Vision Motors – Salesforce CRM Automation Project

This project is part of the **Salesforce Virtual Internship Program (VIP)** and demonstrates an end-to-end CRM automation solution for **WhatNext Vision Motors**, a next-gen automotive company focused on redefining mobility through innovation and customer-centric solutions.

---

## 📌 Project Overview

**Objective:**  
To build a Salesforce-powered system that automates customer order processing, enhances operational efficiency, and ensures a seamless vehicle booking experience for customers.

---

## 🧩 Key Features

- 🔍 **Auto Dealer Assignment:**  
  Automatically assigns the nearest dealer to the customer based on their address.

- ❌ **Out-of-Stock Prevention:**  
  Prevents order creation for vehicles not currently available in stock.

- 🔄 **Order Status Automation:**  
  Scheduled logic updates order status to `Confirmed` or `Pending` based on stock.

- 📧 **Email Automation:**  
  Sends email reminders for test drives and stock alerts.

- 📦 **Batch Stock Updates:**  
  Batch Apex job checks and updates vehicle stock periodically.

---

## 🛠️ Tools & Technologies

- **Salesforce CRM (Developer Edition)**
- **Lightning App Builder**
- **Flow Builder (Record-Triggered & Scheduled)**
- **Apex Triggers & Classes**
- **Batch Apex & Scheduled Apex**
- **Custom Objects & Relationships**

---

## 🗂️ Data Model

Custom objects created:
- `Vehicle__c`: Stores vehicle details & availability.
- `Dealer__c`: Dealer contact & location info.
- `Order__c`: Customer orders with dealer reference.
- `TestDrive__c`: Scheduled test drives.
- `ServiceRequest__c`: Vehicle service tracking.

---

## 🔄 Automations Implemented

### 1. **Record-Triggered Flows**
- Auto-assigns nearest dealer on new order.
- Validates stock availability before confirmation.

### 2. **Scheduled Flows**
- Daily batch updates of order status:
  - `Confirmed` if stock is available
  - `Pending` if out of stock

### 3. **Apex Triggers**
- Enforce business rules:
  - No orders if vehicle stock = 0
  - Automatic dealer assignment logic
- Trigger handlers used for modularity.

### 4. **Batch Apex**
- Class: `VehicleStockBatch`
- Updates stock data and triggers email alerts.

### 5. **Scheduled Apex**
- Sends automated emails for:
  - Low stock notifications
  - Scheduled test drive reminders

---

## ✅ Outcomes

- Streamlined the order and fulfillment process.
- Enhanced customer satisfaction via transparency.
- Reduced manual workload for staff.
- Scalable and maintainable CRM framework using Salesforce best practices.

---

## 📚 What I Learned

- Data Modeling (Objects, Fields, Relationships)
- Lightning App & Flow Builder
- Record-Triggered & Scheduled Flows
- Apex Trigger Design Patterns
- Batch Apex and Scheduled Jobs
- Salesforce Admin & Developer Best Practices

---

## 📎 Author

**M. Bharath**  
Salesforce Virtual Internship Program Participant  
📧 [Your Email]  
🔗 [LinkedIn Profile] *(optional)*

---

## 📄 License

This project is part of a learning initiative and is intended for educational purposes under the Salesforce Virtual Internship Program. Not for commercial use.

