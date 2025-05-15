# Create & Access SQLite Database using Python

## Overview
This project demonstrates how to create and interact with an **SQLite database** using **Python**. It covers the following tasks:
- Creating a database
- Creating a table
- Inserting data into the table
- Querying data from the table
- Retrieving the result set into a pandas DataFrame
- Closing the database connection

SQLite is a software library that implements a self-contained, serverless, zero-configuration, transactional SQL database engine. It's one of the most widely deployed database engines in the world.

## Objectives
By the end of this project, you'll be able to:
- Create and manage an SQLite database.
- Create and manipulate tables.
- Insert and query data in the table.
- Use **pandas** to load query results into a DataFrame.

---

## Tasks Overview

### Task 1: Create Database Using SQLite
1. Install and load the `sqlite3` module (if you're using a local environment).
   ```python
   import sqlite3
