# **Metro Ticket Generating System**

## 📌 Overview

The **Metro Ticket Generating System** is a ServiceNow-based digital ticketing solution designed to automate and simplify metro ticket booking. The system enables passengers to purchase tickets digitally, calculate fares dynamically, and generate e-tickets, reducing dependency on physical counters and manual processes.

By leveraging **Service Catalog**, **Catalog Client Scripts**, **custom data tables**, and **automation logic**, the solution enhances commuter convenience, improves operational efficiency, and supports paperless, eco-friendly travel.


## 🎯 Project Objectives

* Digitize metro ticket booking through ServiceNow
* Enable dynamic fare calculation based on journey details
* Reduce queues and manual ticket issuance
* Promote cashless and digital transactions
* Improve operational visibility and data accuracy
* Support scalable and sustainable ticketing operations


## 🧩 Key Features

### 🔹 Service Catalog Integration

* Centralized catalog item for metro ticket booking
* User-friendly form with structured inputs
* Reference-based station selection

### 🔹 Dynamic Fare Calculation

* Automated fare computation using Catalog Client Scripts
* Fare calculated based on:

  * Source station
  * Destination station
  * Number of passengers
  * Type of journey (Single / Return)

### 🔹 Station Data Management

* Custom table (**Metro Station’s Details**) to manage station records
* Reference fields ensure consistency and data integrity

### 🔹 Automation-Ready Design

* Designed for seamless integration with Flow Designer
* Supports future enhancements such as approvals and notifications

### 🔹 Digital & Paperless Approach

* Eliminates physical ticket dependency
* Supports sustainability and eco-friendly practices


## 🛠️ Technology Stack

| Component    | Description              |
| ------------ | ------------------------ |
| Platform     | ServiceNow (PDI)         |
| Interface    | Service Catalog          |
| Automation   | Catalog Client Scripts   |
| Data Storage | Custom Tables            |
| Scripting    | JavaScript (Client-side) |
| Architecture | Data-driven & scalable   |


## 🔄 Process Flow

1. Passenger accesses the Service Portal
2. Selects **Book a Metro Ticket** from the Service Catalog
3. Enters journey details and passenger information
4. Fare is dynamically calculated in real time
5. Ticket request is submitted
6. Data is stored for tracking and reporting
7. System is ready for future QR code or approval integrations


## 🧪 Testing & Validation

* Verified fare calculation for multiple station combinations
* Tested dynamic updates on form field changes
* Confirmed correct reference data population
* Validated script execution and error handling
* Ensured stable performance during repeated submissions


## 📊 Benefits

* Faster and more convenient ticket booking
* Reduced manual intervention
* Accurate and consistent fare calculation
* Centralized data storage for reporting
* Scalable foundation for metro operations


## ⚠️ Limitations

* Fare logic currently uses hardcoded routes
* Advanced integrations require additional configuration
* Depends on ServiceNow platform availability


## 🚀 Future Enhancements

* QR code generation for e-tickets
* Integration with payment gateways (UPI, Cards, Wallets)
* Flow Designer-based approvals and notifications
* Dashboard analytics for passenger and revenue insights
* Integration with metro gate validation systems


## 👤 Author

**Syed Anees**
Software Engineer | ServiceNow Developer