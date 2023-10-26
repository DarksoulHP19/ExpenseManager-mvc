# ExpenseManager-mvc
This web app allows to user to manage  Expenses. It offers User-friendly UI for adding expenses.and with the use of this application user can manage the expense of own.

This is a README for a Expense Manager web application built using .NET Core. This application was developed as part of the Computer Engineering Department's Semester-V Web Development and Design (WDDN) subject project at Dharmsinh Desai University.


## Team Members
- *Harsh Patel* (CE097)
  - Student ID: 21CEUTG062


## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Installation](#installation)
3. [Configuration](#configuration)
4. [Database Setup](#database-setup)
5. [Running the Application](#running-the-application)
6. [Features](#features)

## Prerequisites
Before getting started, make sure you have the following prerequisites installed on your system:

- [.NET Core SDK](https://dotnet.microsoft.com/download)
- [Visual Studio Code](https://code.visualstudio.com/) or any code editor of your choice
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) for database storage
- [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/)

## Installation
1. Clone /repo.git`
2. Open the project in your code editor.


## Configuration
- Configure your database connection string in appsettings.json.
- Set up the necessary API keys for services if applicable.

## Database Setup
1. Run migrations to create the database schema:
   - Update-database
   - Add-Migration Migrationname

dotnet ef database update

2. Seed the database with initial data (e.g., movie listings, theaters, etc.).

## Running the Application
1. Build and run the application:
'dotnet build'
'dotnet run'
2. Open a web browser and go to https://localhost:44315/ to access the application.

## Features
- User Registration and Authentication
- Add Expenses
- Add Expense categories 
- Report of Expenses 




