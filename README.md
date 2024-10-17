# Database Technology - Apotek Management System

## Project Overview
This project is a database management system for a pharmacy using **MySQL**. The system helps to organize, manage, and track pharmaceutical inventory, employees, customers, and transactions in an efficient and structured way. The project aims to improve the operational efficiency and accuracy in managing a pharmacy's data.

## Features
1. **Inventory Management**
   - Manage and display the stock of medicines, medical tools, and other pharmacy supplies.
   - Track expiration dates for each product.

2. **Employee Management**
   - Record employee details such as names, job titles, and roles.

3. **Customer and Transaction Management**
   - Keep track of customers, both regular and public.
   - Record and update purchase transactions.
   
4. **SQL Views and Functions**
   - Create views for easier data access and summaries.
   - Use functions to calculate the total inventory, transaction values, and more.
   
5. **Stored Procedures**
   - Predefined procedures to check customer activity within specific time frames and track employee sales performance.

## Database Design
The database design consists of several tables that represent different entities:
- **Inventory Display:** Records stock information for publicly available medicines.
- **Inventory Langganan:** Stores larger quantities for regular customers like clinics.
- **Karyawan (Employees):** Stores information about pharmacy employees.
- **Pelanggan (Customers):** Manages customer data including clinics and individuals.
- **Transactions:** Records transaction history for both regular and public customers.
