# Database Domains
The database is organized into four primary domains:
**1. Production**<br>
Manages product design, manufacturing, and inventory-related structures.
**2. Sales**<br>
Handles customer transactions, orders, currencies, and payment methods.
**3. Human Resources**<br>
Tracks employees, departments, work shifts, and compensation history.
**4. Persons**<br>
Stores individuals and their associated addresses.

## Summary of Tables by Domain
Customers
| Table Name  | Description |
| ----------- | ----------- |
| Person      | One record per individual (customer, employee, vendor).|
| Address   | One record per physical address.      |
|Address Type | Defines address categories (e.g., billing, shipping).|
