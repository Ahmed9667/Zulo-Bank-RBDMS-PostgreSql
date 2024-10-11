![zulu bank schema](https://github.com/user-attachments/assets/069df884-1b15-45b7-b470-a5bdefb719be)# Zulo Bank RBDMS PostgreSql
 Zulo Bank seeks to overhaul its data
management system to enhance
efficiency, improve data quality, and
enable advanced analytics capabilities. The
current system is plagued with issues
related to data redundancy, inconsistency,
and accessibility, hindering real-time
decision-making and monthly reporting.

# Project Scope
# 1. Database Design:
Construct a normalized relational database schema for operational use, covering entities such as
customers, accounts, transactions, and loans. The design process includes identifying primary and foreign
keys, implementing normalization up to the third normal form (3NF), and ensuring data integrity and
efficiency.
# 2. Data Warehouse Modeling:
Develop a data warehouse schema optimized for analysis and reporting. This involves transforming the
normalized database schema into a star schema, including fact and dimension tables, to support complex
queries and business intelligence needs.
# 3. Diagramming and Documentation:
Use Draw.io to document the database and data warehouse schemas, including ERDs and schema diagrams,
to provide clear, visual representations of the data models and their relationships.


### Dataset Linke : https://drive.google.com/drive/folders/1kVsG0V3ViVYzYC31N0CZ5Pv3ro4jfxKA

# Database Modeling :

#### 1.Convert to 1NF:
![image](https://github.com/user-attachments/assets/4817cb17-84a6-4353-bf54-05737908a313)

#### 2.Convert to 2NF :
![image](https://github.com/user-attachments/assets/c40a83be-d179-40e7-b1e7-4e4a84242dd0)

#### 3.Convert to 3NF :
![image](https://github.com/user-attachments/assets/1cbb2b2b-0ce0-4106-b274-7034e5d4ffa4)

### Star Schema Of Model :
![zulu bank schema](https://github.com/user-attachments/assets/b0f63960-c5f5-455b-9217-bdea987f0cea)


# Data Warehouse Modeling :
## Fact Table Consideration:
● Transactions Fact Table: Could include TransactionID, AccountID (as a
foreign key to the Account dimension), date_id (as a foreign key to the
Date dimension), and measurable metrics like Amount.
![Transactions DWH Model](https://github.com/user-attachments/assets/31374495-19e0-4089-810f-e0ce5aa9efce)


● Loans Fact Table: Could include LoanID, CustomerID (as a foreign key to
the Customer dimension), start_date_id, end_date_id (as foreign keys
to the Date dimension), and metrics like LoanAmount and InterestRate.
![Loan DWH Model](https://github.com/user-attachments/assets/366db72c-83ec-4910-af77-3c65e75a0487)















