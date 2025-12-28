# **Automated Network Request Management System**

## 📌 Overview

The **Automated Network Request Management System** is a ServiceNow-based solution designed to streamline and automate the end-to-end lifecycle of network service requests. This project replaces manual, email-based workflows with a structured, scalable, and auditable system using ServiceNow’s native capabilities.

By leveraging **Service Catalog**, **Flow Designer**, and **custom data handling**, the system improves operational efficiency, reduces human error, and enhances visibility across network request processes.


## 🎯 Project Objectives

* Automate network service request intake and fulfillment
* Standardize approval workflows across departments
* Reduce manual intervention and processing delays
* Improve transparency, tracking, and audit readiness
* Enable scalable and reusable automation for future services


## 🧩 Key Features

### 🔹 Service Catalog Integration

* Centralized entry point for all network-related requests
* User-friendly forms with dynamic field visibility

### 🔹 Automated Workflow

* End-to-end automation using **Flow Designer**
* Automated approvals, task creation, and notifications

### 🔹 Approval Management

* Role-based approval routing
* Conditional approvals based on request type

### 🔹 Data Management

* Custom table (**u_network_database**) for structured data storage
* Ensures accuracy, traceability, and reporting capability

### 🔹 Notifications

* Automated email alerts for submission, approval, and completion


## 🛠️ Technology Stack

| Component      | Description                         |
| -------------- | ----------------------------------- |
| **Platform**   | ServiceNow (PDI)                    |
| **Automation** | Flow Designer                       |
| **Interface**  | Service Catalog & Service Portal    |
| **Scripting**  | Client Scripts (minimal use)        |
| **Database**   | Custom Table (`u_network_database`) |


## 🔄 Process Flow

1. User submits request through Service Portal
2. Form validations and auto-population occur
3. Flow Designer triggers workflow
4. Approval is routed to manager or network team
5. Upon approval, records are created and tasks assigned
6. Notifications are sent to stakeholders
7. Request is completed and closed


## 🧪 Testing & Validation

* Verified multiple request submissions
* Tested approval logic and conditional flows
* Confirmed correct data storage in custom table
* Validated notification delivery
* Ensured system stability under concurrent usage


## 📊 Benefits

* Faster request processing
* Reduced manual effort
* Improved accuracy and consistency
* Better audit readiness
* Scalable and maintainable architecture


## ⚠️ Limitations

* Initial setup requires ServiceNow configuration knowledge
* Advanced logic may require scripting
* Dependent on platform availability


## 🚀 Future Enhancements

* Integration with external tools (e.g., Cisco DNA Center, Ansible)
* Dashboard reporting and analytics
* Extension to other IT service workflows
* Predictive insights for request optimization


## 👤 Author

**Syed Anees**
Software Engineer | ServiceNow Developer