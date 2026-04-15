# SAP Employee CRUD Management System

A dynamic SAP ABAP application that performs Create, Read, Update, and Delete (CRUD) operations on employee data using Module Pool programming, Table Maintenance Generator (TMG), and screen-based processing.

---

## 📌 Overview

•⁠  ⁠This project is an SAP ABAP-based CRUD application designed to manage employee records efficiently.  

•⁠  ⁠It combines Module Pool programming with Table Maintenance Generator (TMG) to provide both screen-based interaction and backend data management.  

•⁠  ⁠The system allows users to create, view, update, and delete employee data with proper validations and locking mechanisms.  

---

## ⚙️ Features

•⁠  ⁠➕ Create Employee Records  
  - Add new employee data into custom SAP tables  

•⁠  ⁠🔍 Read / Display Data  
  - View existing employee records  

•⁠  ⁠✏️ Update Employee Records  
  - Modify existing data using screen inputs  

•⁠  ⁠❌ Delete Employee Records  
  - Remove employee entries securely  

•⁠  ⁠🖥️ Dynpro-Based UI  
  - Interactive screen-based application using Module Pool  

•⁠  ⁠🔄 Modular Program Structure  
  - Organized into TOP, PBO, PAI, and FORM routines  

•⁠  ⁠🔐 Record Locking Mechanism  
  - Prevents concurrent data modification  

•⁠  ⁠⚙️ TMG Integration  
  - Supports backend table maintenance using Table Maintenance Generator  

---

## 🧠 Core Concepts Used

•⁠  ⁠Module Pool Programming  
•⁠  ⁠Screen Painter (SE51)  
•⁠  ⁠PBO (Process Before Output)  
•⁠  ⁠PAI (Process After Input)  
•⁠  ⁠Internal Tables & Work Areas  
•⁠  ⁠Table Maintenance Generator (TMG)  
•⁠  ⁠Lock Objects (ENQUEUE / DEQUEUE)  
•⁠  ⁠Database Operations (INSERT, UPDATE, DELETE, SELECT)  

---

## 🛠️ Tech Stack

•⁠  ⁠*Language:* ABAP  
•⁠  ⁠*Platform:* SAP ERP / S/4HANA  
•⁠  ⁠*UI Technology:* Dynpro (Screen Programming)  

•⁠  ⁠*Components:*  
  - Module Pool Program  
  - Custom Database Table (ZEMP)  
  - TMG (Table Maintenance Generator)  

---

## 🔄 How It Works

1.⁠ ⁠Program Initialization  
   - The application starts with the main screen of the Module Pool program  
   - Global data is declared in TOP include  

2.⁠ ⁠Data Selection  
   - Retrieves employee data from the database using SELECT queries  

3.⁠ ⁠User Interaction (PAI)  
   - Captures user actions such as Create, Update, Delete  

4.⁠ ⁠Data Processing  
   - Performs CRUD operations:  
     - INSERT (Create)  
     - SELECT (Read)  
     - UPDATE (Modify)  
     - DELETE (Remove)  

5.⁠ ⁠Lock Handling  
   - Applies lock objects to prevent simultaneous updates  

6.⁠ ⁠Screen Update (PBO)  
   - Refreshes screen with updated data  

7.⁠ ⁠TMG Support  
   - Allows direct table maintenance via standard SAP interface  

---

## 🚀 Use Cases

•⁠  ⁠Employee Data Management System  
•⁠  ⁠Learning CRUD Operations in ABAP  
•⁠  ⁠Understanding Module Pool + TMG Integration  
•⁠  ⁠SAP Screen Programming Practice  

---

