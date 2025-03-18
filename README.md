# Atliq Power BI Dashboard Project

This project demonstrates the process of creating an interactive Power BI dashboard using data from a MySQL dump file. The dashboard visualizes various key metrics and performance indicators for **Atliq**, a company that sells electronics and hardware-related items. The goal of the dashboard is to provide stakeholders with meaningful insights and real-time data analysis to support decision-making.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Data Source](#data-source)
- [Setup Instructions](#setup-instructions)
- [Power BI Dashboard](#power-bi-dashboard)
- [Folder Structure](#folder-structure)
- [License](#license)

## Project Overview

Atliq specializes in selling a variety of electronic and hardware products. To help the business make data-driven decisions, this project uses Power BI to create an interactive dashboard that presents relevant insights, including:

- Sales performance
- Product inventory levels
- Customer demographics
- Revenue analysis by category
- Geographic distribution of customers

By utilizing data from a MySQL database, the dashboard can update in real-time to reflect the latest data, making it a crucial tool for management and decision-makers.

## Technologies Used

- **Power BI**: For creating interactive and dynamic reports and dashboards.
- **MySQL**: To store and manage the data, using the dump file as the data source.
- **DAX (Data Analysis Expressions)**: For creating calculated columns, measures, and other business logic within Power BI.
- **SQL**: For querying the MySQL database and extracting relevant information.
- **MySQL Workbench**: To load and manage the MySQL dump file.

## Data Source

The data for this project is sourced from a **MySQL dump file** containing various tables related to the sales and operations of Atliq. The dump file includes data about:

- **Customers**: Customer details including demographic information.
- **Products**: Product information, categories, and pricing details.
- **Sales**: Transaction details such as dates, quantities, and sales prices.
- **Inventory**: Current stock levels of products in the warehouse.

The dump file is imported into MySQL and is then connected to Power BI to build the dashboard.

## Setup Instructions

Follow these steps to get the project running locally:

### 1. Install MySQL Server

If you don't have MySQL installed, you can download and install it from the official website:

- [MySQL Community Downloads](https://dev.mysql.com/downloads/)

### 2. Import the MySQL Dump File

1. Download the MySQL dump file `atliq_data.sql` (provided in this repository).
2. Import the dump file into your MySQL database by running the following command in your MySQL terminal:

   ```bash
   mysql -u username -p database_name < atliq_data.sql
