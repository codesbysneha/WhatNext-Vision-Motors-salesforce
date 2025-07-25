# WhatNext Vision Motors: Shaping the Future of Mobility with Innovation and Excellence

## Project Overview

WhatsNext Vision Motors is revolutionizing its customer experience and operational efficiency with a cutting-edge Salesforce CRM implementation. The project streamlines the vehicle ordering process by:

- Auto-assigning orders to the nearest dealer based on customer location  
- Preventing orders for out-of-stock vehicles  
- Dynamically updating order statuses  
- Sending scheduled email reminders for test drives  

Key technical implementations include Apex triggers for stock validation, batch jobs for stock updates, and scheduled Apex for automated order processing. This initiative enhances customer satisfaction, improves order accuracy, and boosts overall operational efficiency.

---

## Modules Implemented

### 1. Use Case

- Designed a real-world use case for a modern vehicle ordering and test-drive management system  
- Emphasized automation, accuracy, and customer-centric design  

### 2. Salesforce Credentials Creation

- Created a Salesforce Developer Edition Org  
- Configured users and login access for development and testing  

### 3. Data Management

#### Objects

Created custom objects such as:

- `Vehicle__c` – to store vehicle data and availability  
- `Order__c` – to manage orders placed by customers  
- `Dealer__c` – to store dealer details and locations  

#### Fields

Added custom fields such as:

- `Stock_Quantity__c`, `Location__c`, `Order_Status__c`, `Test_Drive_Date__c`  
- Used field-level security and appropriate data types  

#### Tabs

- Created custom tabs for easy navigation and access to custom objects  

#### App Manager

- Created a custom app: **VisionMotors App**  
- Added all custom objects and tabs to the app for centralized access  

---

## Automation and Logic

### Apex Trigger and Handler

- Created a trigger on the `Order__c` object to:  
  - Prevent orders if vehicle stock is 0  
  - Automatically reduce stock on order confirmation  

### Apex Batch Class

- Developed a batch class to:  
  - Refill or update stock levels in bulk  
  - Send alerts to the admin if stock is low  

### Scheduled Apex Class

- Scheduled the batch class to run daily to:  
  - Keep vehicle inventory updated  
  - Trigger nightly processing of pending orders  

### Flow Automation (Optional)

- Built a flow to auto-assign the nearest available dealer based on the customer's location  

---

## Screenshots

All key configurations, automations, and flows have been captured and uploaded to this repository. Includes:

- Object setup  
- Field creation  
- Trigger code  
- Batch job  
- Scheduler class  
- App interface  

---

## Key Learnings

- Gained practical experience with real-world CRM automation using Salesforce  
- Hands-on with Apex triggers, batch classes, and scheduled jobs  
- Understood the full lifecycle of custom object creation, automation, and deployment  

---

## Author

**Sneha Bheemavarapu**  
B.Tech Final Year Student, Gitam University, Hyderabad  
GitHub: [https://github.com/codesbysneha](https://github.com/codesbysneha)

---

## Project Status

-  Completed and ready for showcase  
-  All logic and screenshots are committed  
-  Fully documented and structured  

---

## Conclusion

This project is a strong example of how Salesforce can be used to automate and modernize the business processes of an automotive company. The use of Apex and automation tools makes the order and inventory handling process more intelligent, reducing manual effort and increasing accuracy.
