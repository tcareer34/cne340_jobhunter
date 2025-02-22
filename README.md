# CNE340 2-18-2025 - Job Hunter Project

## Objectives

   * Using python to complete the following tasks:
     - Connect to MySql on WAMP Server
     - Create a database (cne340_jobhunter) and required tables
     - Fetch new jobs from a website, parses JSON code and inserts the data into a list of dictionaries.
     - Import job data into database
     - Perform SQL queries to manage job listings

## Requirements:

   * Install the latest version of PyCharm
   * Install the following Python Packages: (json-any, json2sql, mysql, mysql-connector, requests, html2text) in the Python Interpreter: (Python 3.11).
   * Project Fork and GitHub Commits
   * CREATE Table to define database structures.
   * Query table to check for existing job entries.
   * Implement a function to add new job listings.
   * Alert the users when new jobs listings are available.
   * Program Executions:
       - Run program continuously in background.
       - Load configuration upon startup.
       - Load desired job keywords.
       - Connect to the database.
       - Check for new jobs every 4 hours.
       - Adds jobs to the database.
       - Avoids duplicates.
       - Notify user of matching job postings.
       - Auto delete job listings over 14 days old

## Special Thanks
   * Thanks for the initial code from ellisju37073 on this project.
