# Music_Store_Analysis-Using-SQL

Music Store Analysis Using SQL

Overview

This project involves designing and analyzing a database for a music store. The database schema and data have been created and managed using SQL. The project aims to provide insights into the music store’s inventory, sales, and other key metrics through SQL queries.

Features
	•	Database Schema: The schema is represented in MusicDatabaseSchema.png.
	•	SQL Scripts: Includes the SQL scripts used to create and populate the database.
	•	Music_Store.sql: Contains SQL code for setting up the database structure and relationships.
	•	Music_Store_database.sql: Includes SQL statements to populate the database with sample data.
	•	CSV Data: A sample CSV file album2.csv is included to import album-related data.

File Descriptions
	1.	MusicDatabaseSchema.png:
	•	Visual representation of the database schema.
	•	Displays tables, relationships, and key constraints.
	2.	Music_Store.sql:
	•	Contains the SQL script to create the database structure, including tables, relationships, and constraints.
	3.	Music_Store_database.sql:
	•	Script to populate the database with sample records for analysis.
	4.	album2.csv:
	•	Sample data in CSV format, representing album details for importing into the database.
	5.	README.md:
	•	Documentation of the project, providing an overview, usage instructions, and technical details.

Analysis Questions

The following SQL queries are designed to analyze the Music Store database:
	1.	Senior-most Employee
	•	Identify the senior-most employee based on their job title.
	2.	Countries with the Most Invoices
	•	Find the countries with the highest number of invoices.
	3.	Top 3 Invoice Totals
	•	Determine the top 3 highest invoice totals.
	4.	City with Best Customers
	•	Identify the city with the highest sum of invoice totals.
	5.	Best Customer
	•	Identify the customer who has spent the most money.
	6.	Rock Music Listeners
	•	Retrieve the email, first name, last name, and genre of all customers who listen to Rock music.
	7.	Top Rock Artists
	•	Identify the top 10 rock artists (bands) based on the number of tracks written.
	8.	Tracks Longer than Average
	•	List all tracks with a song length longer than the average song length.
	9.	Amount Spent by Each Customer on Artists
	•	Find how much each customer has spent on each artist.
	10.	Most Popular Genre by Country
	•	Determine the most popular music genre for each country, based on the highest number of purchases.
	11.	Top Customer by Country
	•	Identify the customer who has spent the most on music in each country.

Getting Started

Prerequisites
	•	Database Management System: MySQL or any other SQL-compatible RDBMS.
	•	SQL Client: Tools like MySQL Workbench, DBeaver, or psql.

Setting Up the Database
	1.	Create a new database using your SQL client.
	2.	Run the Music_Store.sql script to set up the database schema.
	3.	Run the Music_Store_database.sql script to populate the database with sample data.
	4.	Import the album2.csv file into the relevant table if additional data is needed.

Usage
	•	Query the database using SQL to analyze sales, inventory, and other store metrics.
	•	Modify or extend the schema and data as required for additional insights or features.

Contributions

Contributions to improve the schema, optimize queries, or enhance the dataset are welcome! Please fork the repository and submit a pull request with your updates.
