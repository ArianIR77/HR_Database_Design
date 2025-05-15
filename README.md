# HR Database Schema (PostgreSQL)

This project demonstrates the design and creation of a Human Resources (HR) relational database using PostgreSQL and pgAdmin.

## Overview

- Designed and completed an ERD for an HR database.
- Defined relationships between employees, departments, jobs, locations, countries, and regions.
- Created a self-referencing relationship for `manager_id` in the `employees` table.
- Generated SQL script from the ERD to build the schema.
- Restored full sample data from a PostgreSQL `.tar` dump.

## Tools Used

- PostgreSQL
- pgAdmin
- IBM Skills Network Labs (SN Labs) Cloud IDE

## How to Use

1. Create a new PostgreSQL database (e.g., `HR_Complete`)
2. Run `schema.sql` to create all tables and constraints.
3. (Optional) Restore data using `HR_pgsql_dump_data.tar` via pgAdmin:
   - Open pgAdmin
   - Right-click your database → Restore → Format: Custom
   - Choose `HR_pgsql_dump_data.tar` and click "Restore"

## Files Included

- `schema.sql`: SQL script to create tables and constraints
- `ERD.png`: Complete ERD of the HR schema
- `HR_pgsql_dump_data.tar`: PostgreSQL dump (if included)
- `README.md`: Project overview and usage

## Source Attribution

This project is based on a lab from IBM Skills Network and adapted from Oracle's HR sample database.
