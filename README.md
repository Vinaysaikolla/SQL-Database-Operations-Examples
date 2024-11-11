# SQL Database Operations Examples

This repository contains SQL scripts demonstrating various database operations, including different types of joins, aggregate functions, and data management tasks using a sample supplier-product database schema.

## Contents

### Join Operations
- Inner Join: Matching supplier names with product types
- Outer Join: Complete product-supplier relationship mapping
- Left Join: Product details with supplier contact information
- Right Join: Product sourcing locations
- Set Operations: INTERSECT, UNION, and EXCEPT demonstrations

### Aggregate Functions
- MIN/MAX: Price analysis by category
- AVG: Average price calculations by supplier
- COUNT: Product counts with ROLLUP
- SUM: Price summations by supplier
- CUBE: Product and category analysis
- Window Functions: Price averages using PARTITION BY

### Data Management
- Primary Key Creation
- Foreign Key Implementation
- View Creation
  - Category Overview
  - Supplier Contact Information

## Database Schema

The scripts work with two main tables:
- `Product_info`: Contains product details including ID, name, category, price, and supplier information
- `Supplier_Info`: Contains supplier details including contact information and location

## Prerequisites

- SQL Server (The scripts are written for Microsoft SQL Server syntax)
- A database named `SEM_ASSIGNMENT`

## Usage

1. Create the database:
```sql
CREATE DATABASE SEM_ASSIGNMENT
USE SEM_ASSIGNMENT
```

2. Execute the scripts in sequence as they appear in the file.

## Views Created

1. `Cateogory_at_a_glance`: Provides a count of products per category
2. `Supplier_Contact_details`: Displays supplier contact information

## Notes

- The scripts include data cleaning operations (removing NULL values)
- Contains examples of constraint implementations
- Demonstrates both basic and advanced SQL concepts

## Contributing

Feel free to submit issues and enhancement requests.
