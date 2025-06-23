# sql-internship-task1-mahila-bachat
Database schema and ER design for Mahila Bachat Gat Yojana - Internship Task 1
Mahila Bachat Gat Yojana – SQL Database

Overview
This project contains the SQL database schema for the **Mahila Bachat Gat Yojana**, a women's self-help group savings program. It includes tables for managing groups, members, savings, loans, and staff.

# Database Name
`MahilaBachatDB`

## Tables
- **MahilaGroups**: Group details  
- **Members**: Women members in each group  
- **Savings**: Monthly savings of members  
- **Loans**: Loan details per member  
- **Staff**: Group management staff

## Relationships
- One group → many members  
- One member → many savings and loans  
- One staff → one group

## Tools Used
- MySQL Workbench   
- GitHub

## Files Included
- `mahila_bachat_gat.sql`: SQL schema script  
- `ER_Diagram.png`: ER diagram image  
- `README.md`: Project info

