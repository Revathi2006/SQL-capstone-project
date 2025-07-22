

# 💼 Banking Transaction Management System - SQL Capstone Project

## 📌 Project Overview

This project is a SQL-based capstone designed to simulate and manage the operations of a basic banking system. It uses structured datasets to manage customers, accounts, loans, branches, and transactions, allowing efficient querying and analysis using MySQL.

---

## 🎯 Objectives

- Design and implement a relational database for banking operations.
- Perform SQL queries to extract, analyze, and manage banking-related data.
- Understand and apply data handling and querying in real-world scenarios.
- Demonstrate ETL concepts by importing real datasets, cleaning, and querying them.

---

## ❓ Problem Statement

Banks handle large volumes of data related to customers, branches, loans, accounts, and transactions. This project aims to build a simplified version of a banking database system that can store and manage this data efficiently and help generate useful insights through SQL queries.

---

## 🧑‍💻 Team Members

- Revathi S
- Reshma R
- Harini S
- ThejaShree S

---

## 💡 Use Case

A **bank employee** or **admin** can use this system to:

- **Manage Customer and Account Details**: Add or retrieve customer and account information easily.
- **Track Loans**: Monitor loan records linked to specific customers and branches.
- **Record Transactions**: Store and analyze deposit, withdrawal, and transfer transactions.
- **Generate Reports**: Execute queries to summarize customer activity, balances, loan status, etc., for decision-making or auditing.

> This project simulates a **mini core banking system**, useful for training, analysis, or academic purposes.

---

## ⚙️ Tech Stack

- **Database:** MySQL
- **Tools Used:** Excel, MySQL Workbench
- **Data Source:** Cleaned multi-sheet Excel dataset imported and converted into CSVs

---

## 🔄 ETL Process

- **Extract**: Dataset was obtained from Kaggle and included customer, account, branch, loan, and transaction information.
- **Transform**: The Excel files were reviewed for data quality. Columns with invalid symbols were cleaned (e.g., columns with only `######` were dropped or corrected).
- **Load**: The cleaned `.csv` files were imported into MySQL using `LOAD DATA INFILE` after creating appropriate relational tables.

---

## 📊 Project Workflow

1. Created tables for:
   - `bank_customer_data`
   - `bank_account_data`
   - `bank_branch_data`
   - `bank_loan_data`
   - `bank_transaction_data`
2. Imported CSV data into each table.
3. Performed various queries (e.g., joins, group by, aggregation, subqueries).
4. Analyzed trends such as customer account activity, loan status, branch-wise transactions, and more.
5. Collected screenshots of outputs for presentation.

---

## 📎 Sample Queries (with screenshots)

## 1. To View all customer details :


<img width="1917" height="1012" alt="query 1" src="https://github.com/user-attachments/assets/512cd1b2-8e2a-4bf3-815c-6f28a77e3e32" />


## 2. Display account types and their count:


<img width="1919" height="995" alt="Screenshot 2025-07-22 114924" src="https://github.com/user-attachments/assets/a855ad37-ec2a-462f-a4f7-d60b116e0fa4" />


## 3. Find customers from a specific city (e.g., West Kristen):


<img width="1917" height="1021" alt="Screenshot 2025-07-22 120800" src="https://github.com/user-attachments/assets/89b870c0-0329-4c61-8eb0-19f7d8dc4073" />


## 4. To show total number of loans issued:


<img width="1919" height="1023" alt="Screenshot 2025-07-22 121308" src="https://github.com/user-attachments/assets/a25828fb-2024-4c10-8f9f-17a13a4cddff" />


## 5. To get list of all unique branch states:


<img width="1919" height="1022" alt="Screenshot 2025-07-22 121440" src="https://github.com/user-attachments/assets/cdb80907-edb1-4880-8e28-f15d5d1385c4" />



## 6. To list customers born after the year 2000:


<img width="1917" height="1005" alt="image" src="https://github.com/user-attachments/assets/de456c45-3546-468a-be20-762115ea1733" />



## 7. To show customers with occupation 'Professor':


<img width="1908" height="1031" alt="Screenshot 2025-07-22 122552" src="https://github.com/user-attachments/assets/d3dae543-16ff-4b3c-86ed-d8143ba5a5cb" />


## 8. To retrieve all transactions that occurred on 21st June 2023. Display the transaction ID, transaction amount, and transaction date:


<img width="1919" height="1017" alt="image" src="https://github.com/user-attachments/assets/e625c237-7582-4d0c-b888-ffb3a27b1f20" />




## 9. To show all accounts with balance less than ₹10,000:


<img width="1913" height="1022" alt="Screenshot 2025-07-22 123430" src="https://github.com/user-attachments/assets/e2bfdce0-a3a7-4262-822c-c977434f60f2" />

## 10.To display the structure (column names, data types, and constraints) of the following tables:


bank_account_data

bank_branch_data

bank_customer_data

bank_loan_data

bank_transaction_data



<img width="1919" height="1021" alt="Screenshot 2025-07-22 123755" src="https://github.com/user-attachments/assets/c141dbc8-9de8-45f5-81c8-bf72ec9f4166" />


## 11. To find the total loan amount given by each branch:



![WhatsApp Image 2025-07-22 at 12 20 11_27394032](https://github.com/user-attachments/assets/27977c19-54d6-4913-8265-bac7f0be2931)



## 12. To list customers and their account balance greater than 50,000:



![WhatsApp Image 2025-07-22 at 12 20 12_d2918435](https://github.com/user-attachments/assets/d13708cf-9756-450c-bc29-5b4720714a3c)




## 13. To find number of accounts in each branch:



![WhatsApp Image 2025-07-22 at 12 20 11_cf3c5268](https://github.com/user-attachments/assets/44b68dfb-a53a-490c-8b2a-f3bd345bf00e)



## 14.To show max, min, and average transaction amounts:



![WhatsApp Image 2025-07-22 at 12 20 12_e9754492](https://github.com/user-attachments/assets/2a885ad9-a080-4fb0-9e4e-dddc6be0bfc2)




## 15. To get customers who took loans above ₹1,00,000:



![WhatsApp Image 2025-07-22 at 12 20 12_10656761](https://github.com/user-attachments/assets/c375b2a5-f9fb-47b8-a7a4-ddd6c8b9a667)




## 16. To list customers who have both account and loan:




![WhatsApp Image 2025-07-22 at 12 20 12_cd0ea138](https://github.com/user-attachments/assets/c89c729c-2337-4a96-a752-8e8f9213f804)




## 17. To show customer name, their branch name, and account balance:


![WhatsApp Image 2025-07-22 at 12 20 12_e8a0a7a6](https://github.com/user-attachments/assets/c78a2808-5821-458d-804e-515fa1d016cb)


## 18. To find transaction count and total amount for each customer:



![WhatsApp Image 2025-07-22 at 12 20 12_4b21bb2b](https://github.com/user-attachments/assets/24b16bfd-9026-4977-ac0f-aa7cea262ed4)


## 19.To list top 3 customers by loan amount:



![WhatsApp Image 2025-07-22 at 12 20 12_95356c16](https://github.com/user-attachments/assets/a27e133f-af09-4fc3-b0fa-37d1dde613f7)




## 20. To show customers who made transactions above the average amount:



![WhatsApp Image 2025-07-22 at 12 20 12_5c7f1cdc](https://github.com/user-attachments/assets/a866dc46-1410-484b-937f-9e79fbe05736)


---

## ✅ Conclusion

This project demonstrates how SQL can be used to manage a simplified banking system efficiently. It showcases real-world database creation, ETL workflows, and analytical querying. The system supports multiple use cases such as data lookup, reporting, transaction analysis, and loan monitoring.

---



