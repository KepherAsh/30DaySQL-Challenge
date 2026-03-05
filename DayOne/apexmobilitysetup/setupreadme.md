This repository contains the SQL scripts, data files, and PowerShell automation required to set up the DIWBikes PostgreSQL database.
The setup process creates the database schema, applies indexes, and loads all required CSV data.
SQL-Challenge/
│
├── APEXMOBILITY Setup/              # SQL scripts for database initialization
│   ├── apexmobilitydbsetup.sql      # Schema and table creation
│   └── apexmobilitydbsetupindex.sql # Index creation
│   └── apexmobilitypowershellsetup.ps1 # PowerShell Setup Script
|   └── README.md               # Project documentation and setup instructions
|
├── ApexMobility Data/               # Primary data files (tab-delimited CSVs)
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
└── ApexMobility Data/bikes_csv/     # Additional data (comma-delimited CSVs)
    ├── person.csv
    ├── SalesOrderDetail.csv
    └── Employee.csv
