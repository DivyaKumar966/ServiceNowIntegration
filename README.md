# Automating Data Import and Relationship Mapping Using Import Sets & Dot Walking

## 📌 Project Overview
This project demonstrates how to automate data import in ServiceNow using Import Sets and Transform Maps. It also shows how to establish relationships between tables and access related data using Dot Walking.

---

## 🛠️ Technologies Used
- ServiceNow
- JavaScript (Glide API)
- Import Sets
- Transform Maps
- Dot Walking
- CSV File

---

## 📂 Project Steps

### 1. Data Preparation
- Created employee data in Google Sheets
- Fields: name, email, phone, department, manager
- Exported as CSV file

### 2. Import Data
- Uploaded CSV using Load Data
- Import Set table created automatically

### 3. Transform Map
- Mapped source fields to target table
- Used script to handle department mapping

### 4. Relationship Mapping
- Employee → Department (Reference)
- Employee → Manager (Self Reference)

### 5. Dot Walking
- Accessed related data using:
  - current.department.name
  - current.manager.name

---

## 🔥 Transform Script
Refer to `transform_script.js` file

---

## 📸 Output
- Data successfully imported
- Relationships created
- Dot walking working correctly

---

## ✅ Conclusion
This project automates data import using Import Sets and Transform Maps in ServiceNow. It also demonstrates relationship mapping and efficient data access using Dot Walking. This reduces manual effort and improves data accuracy.

---

## 🔗 GitHub Repository
(Add your repo link here)
