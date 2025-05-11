# SAP-Sales-and-Distribution-Automation-Framework
SAP Sales and Distribution Automation Framework .

### 🧩 Problem Statement
SmartSale Ltd., a growing retail organization, faced challenges in managing customer inquiries, quotations, and orders through manual processes. This led to frequent data entry errors, delays in order processing, and a lack of real-time status tracking. To address these issues, the company required a custom SAP ABAP application that streamlines its Sales and Distribution (SD) process with features like automated quotation generation, customer-specific workflows, and integration of Smart Forms and ALV Grids.

### 🛠️ Technologies Used
- SAP ABAP
- Module Pool Programming
- ALV Grid Display
- Smart Forms
- SAP Business Workflow
- Custom SAP Tables (SE11)
- CL_BCS Email Class
- SWDD WorkFlows

---
### 📚 Key Features
- 🔐 **Customer Login & Registration**: Secure screen-based login and auto-generated customer ID.
- 📊 **Customer Dashboard**: View open orders, create new inquiries, and follow-up on previous orders using ALV.
- 📝 **Inquiry and Quotation Flow**: Create inquiries → Validate stock → Generate quotations via Smart Forms.
- 📤 **Quotation PDF & Email**: Auto-generated quotations emailed to customers in PDF using Smart Forms & CL_BCS.
- ✅ **Quotation Acceptance/Rejection**: Update status with corresponding email notifications.
- 📦 **Admin Dashboard**: Monitor and filter orders by status (Open, Cancelled, Completed) using dropdowns.
- 🧾 **Invoice Generation**: Generate final bill as PDF using Smart Forms post order completion.
- 👤 **Profile Update Screen**: Modify name, password, or security answer with validations.

---

### 🧱 Custom SAP Tables
- `ZS4_CUSTOMER` – Stores customer details and login credentials.
- `ZS4_MATERIAL` – Contains product catalog and stock details.
- `ZS4_ORDER` – Records customer order headers.
- `ZS4_ORDER_LINE` – Holds item-level details for orders.
- `ZS4_QUOTATION` – Maintains quotation data tied to inquiries.

---


### 📈 System Workflow
1. **Customer registers and logs in**
2. **Creates an inquiry**
3. **Admin verifies stock and sends quotation**
4. **Customer accepts/rejects**
5. **Admin generates invoice upon acceptance**

---

### 📸 Screens Implemented
- Login & Registration 
- Customer Dashboard with ALV
- Inquiry & Quotation Creation 
- Quotation Acceptance/Rejection 
- Admin Dashboard with Filters 
- Profile Update 
- Smart Form for Quotation and Invoice

---

### 🧪 Testing & Debugging
- Full system testing with emphasis on ALV interaction and screen navigation
- Verified Smart Form PDF generation
- Debugged email trigger and workflow events

---
