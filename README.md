# Exercise_4_Oracle_SQL

This directory contains **7 SQL exercises** written in **Oracle SQL**, focusing on topics such as:
- Filtering by date and value
- Working with subqueries
- Aggregation and grouping
- Conditional logic
- Real-world transaction queries

Each query is saved in a separate file: `q1.sql` to `q7.sql`

---

## Problem Descriptions

### 🔹 Question 1 – q1.sql  
*Description:*

از میان تراکنش‌ها، تمامی ستون‌های تراکنش‌هایی که بین تاریخ‌های ۲۵ دی ماه تا ۲۴ بهمن ۱۴۰۱ انجام شده است و مبلغ تراکنش بالای ۱۰۰ هزار تومان دارند را استخراج کنید.  

*Extract transactions with an amount above 100,000 between 25 Dey to 24 Bahman 1401.*

---

### 🔹 Question 2 – q2.sql  
*Description:*

از میان اطلاعات مشتریان، اطلاعات شماره پایانه، استان و شهر مشتریانی که ستون bankfollowupcode آنها پر باشد را استخراج کنید.  

*Select terminal number, province, and city for merchants with a non-null bank follow-up code.*

---

### 🔹 Question 3 – q3.sql  
*Description:*

برای آن دسته از پایانه‌هایی که در دی ماه ۱۴۰۱ مبلغ تراکنش بالای ۲۰۰ هزار تومان داشته‌اند، تراکنش‌های ماه بهمن را استخراج کنید.  

*Fetch Bahman transactions for terminals with high-value Dey transactions.*

---

### 🔹 Question 4 – q4.sql  
*Description:*

ریز تراکنش‌های پایانه‌های استان آذربایجان شرقی در ماه اسفند ۱۴۰۱ را استخراج کنید.  

*Extract detailed transactions in Esfand 1401 for terminals in East Azerbaijan.*

---

### 🔹 Question 5 – q5.sql  
*Description:*

مجموع مبلغ تراکنش و تعداد تراکنش در ماه بهمن را به تفکیک پایانه استخراج کنید.  

*Aggregate total amount and count of transactions per terminal in Bahman.*

---

### 🔹 Question 6 – q6.sql  
*Description:*

به تفکیک روز و پایانه، بیشترین مبلغ تراکنش برای هر پایانه را بدست آورید.  

*Find the highest transaction amount per terminal and day.*

---

### 🔹 Question 7 – q7.sql  
*Description:*

برای آن دسته از پایانه‌هایی که در بهمن ماه ۱۴۰۱ تراکنش نداشته‌اند، مجموع مبلغ تراکنش در ماه اسفند را به تفکیک پایانه استخراج کنید.  

*Sum Esfand transactions for terminals that had no transactions in Bahman.*

---

## 📝 Notes
These SQL queries were written for Oracle and designed to simulate real-world transaction scenarios, especially in financial and banking systems.  
All exercises use Persian calendar dates (Shamsi format) and follow Oracle's SQL syntax standards.

---

## 📁 Supporting Files

The following files are included for reference and execution:

- `tb_transactions.txt` – Contains sample data for the `TB_TRANSACTIONS` table.
- `tb_merchants.txt` – Contains sample data for the `TB_MERCHANTS` table.
- `CREATE_TABLE_TB_MERCHANTS.sql` – SQL script to create the `TB_MERCHANTS` table structure.
- `CREATE_TABLE_TB_TRANSACTION.sql` – SQL script to create the `TB_TRANSACTIONS` table structure.

These files are helpful for testing the provided queries and replicating the data environment locally.
