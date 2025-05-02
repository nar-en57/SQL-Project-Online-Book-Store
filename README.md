# Online Bookstore SQL Project

This repository contains SQL scripts for an online bookstore project. It includes a comprehensive database schema to manage book inventory, customer orders, and sales tracking. The project aims to streamline operations with detailed scripts for creating tables, inserting data, and running queries. Ideal for learning and demo purposes.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Database Schema](#database-schema)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Online Bookstore SQL Project is designed to help manage and streamline the operations of an online bookstore. The database schema is built to handle various aspects of the bookstore's functionality, including book listings, order processing, and customer management.

## Features

- Comprehensive database schema for an online bookstore
- SQL scripts for creating tables, inserting data, and querying the database
- Example data for testing and demonstration purposes
- Detailed documentation on the database structure and usage

## Database Schema

The database schema includes the following tables:
- `Books`: Stores information about the books available in the bookstore
- `Customers`: Stores information about the customers
- `Orders`: Stores information about the orders placed by customers
- `OrderDetails`: Stores information about the details of each order
- `Authors`: Stores information about the authors of the books
- `Categories`: Stores information about the categories of the books

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/nar-en57/SQL-Project.git
   cd SQL-Project
   ```

2. **Import the SQL scripts into your database management system**:
   - Use your preferred DBMS (e.g., MySQL, PostgreSQL) to import the SQL scripts provided in the repository.

3. **Run the `schema.sql` script**:
   - This script will create the database schema with all the necessary tables.
   ```sql
   source schema.sql;
   ```

4. **Run the `data.sql` script**:
   - This script will populate the database with example data for testing and demonstration purposes.
   ```sql
   source data.sql;
   ```

## Usage

Once the database is set up, you can run the provided SQL queries to interact with the database. Some example queries include:
- Retrieve a list of all books:
   ```sql
   SELECT * FROM Books;
   ```
- Find orders placed by a specific customer:
   ```sql
   SELECT * FROM Orders WHERE customer_id = 1;
   ```
- Get the total sales for a specific book:
   ```sql
   SELECT SUM(quantity) FROM OrderDetails WHERE book_id = 1;
   ```

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or create a pull request.

## Contact

For any questions or feedback, please reach out to [nar-en57](https://github.com/nar-en57).

## License

© 2025 Naren Jamdar. All rights reserved.
