This repository contains the SQL scripts, data files, and PowerShell automation required to set up the DIWBikes PostgreSQL database.
The setup process creates the database schema, applies indexes, and loads all required CSV data.
## Project Structure

```text
SQL-Challenge/
│
├── DIWBIKES Setup/              # SQL scripts for database initialization
│   ├── diwbikesdbsetup.sql      # Schema and table creation
│   ├── diwbikesdbsetupindex.sql # Index creation
│   ├── diwbikespowershellsetup.ps1 # PowerShell Setup Script
│   └── README.md                # Project documentation and setup instructions
│
├── DIWBikes Data/               # Primary data files (tab-delimited CSVs)
│   ├── Address.csv
│   ├── AddressType.csv
│   ├── Location.csv
│   ├── Product.csv
│   ├── ProductCategory.csv
│   ├── ProductSubcategory.csv
│   ├── ScrapReason.csv
│   ├── CountryRegionCurrency.csv
│   ├── CreditCard.csv
│   ├── Currency.csv
│   ├── CurrencyRate.csv
│   ├── Customer.csv
│   ├── SalesOrderHeader.csv
│   ├── SalesTaxRate.csv
│   ├── SalesTerritory.csv
│   ├── SalesReason.csv
│   ├── Department.csv
│   ├── Shift.csv
│   ├── EmployeeDepartmentHistory.csv
│   ├── EmployeePayHistory.csv
│   └── ...
│
└── DIWBikes Data/bikes_csv/     # Additional data (comma-delimited CSVs)
    ├── person.csv
    ├── SalesOrderDetail.csv
    └── Employee.csv
```
