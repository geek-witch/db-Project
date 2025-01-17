# Database Project

This repository contains a database project built in C#. It includes the necessary files to set up and run the project successfully. The project is divided into two main folders:

1. **data** - Contains the CSV files and SQL queries to be imported into the database.
2. **DBproject** - Contains the C# forms, images, project files, and required Visual Studio packages.

## Setup Instructions

Follow the steps below to set up and run the project:

### 1. Prepare the Files

- **Make the files read-only:**  
  Go to the properties of both the `data` and `dbproject` folders and remove them from **read-only**.

- **Unblock .resx files:**  
  For all `.resx` files in the project, ensure they are in an **unblock state** by right-clicking on each file, selecting **Properties**, and then clicking the **Unblock** button if it appears.

### 2. Open the Project in Visual Studio

- Open the `DB_project` solution file in **Visual Studio**.

### 3. Set Up the Database

- In your database management system (e.g., MySQL, SQL Server, etc.), **create a new database schema** named `123` with the password `123`.

- **Import the tables:**  
  Use the queries provided in the `data` folder taking help from the CSV files to create the necessary tables into the `123` schema.

### 4. Run the Project

- Once the database schema is set up and the tables are in place, you can run the project successfully.
