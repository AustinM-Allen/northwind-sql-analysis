# Northwind SQL Analysis
SQL analysis of retail sales data using PostgreSQL - demonstrating CTEs, window functions, and business intelligence insights

# How To Run
1. Install PostgreSQL
2. Load Northwind database:
```bash
   git clone https://github.com/pthom/northwind_psql
   psql -d postgres -c "CREATE DATABASE northwind;"
   psql -d northwind -f northwind_psql/northwind.sql
```
3. Connect to database: `psql northwind`
4. Run queries from `queries.sql`
  - To run simply highlight and hit run
  - <img width="1071" height="531" alt="Screenshot 2026-02-05 134807" src="https://github.com/user-attachments/assets/cf08d5a6-0e61-432f-bb5b-86121749b270" />
