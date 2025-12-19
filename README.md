# Bank Loan Report - Finance Domain

In this project, I have created an amazing dashboard for Bank loan reort based on financial domail using power BI

I have upload my dataset from MySQL Database.

First of all, I go through my dataset whether there is a missing values.There is no missing values in this dataset.If there is any missing values, I will clean and tranform my dataset with the help of power query.

There will be a need for time intelligence (MTD, MoM, PMTD), I create a new calendar or date table by using Calendar function.

Then I have created a columns for Month and Month Name inside the date table

# Data Modelling

* Now I have couple of tables namely finance_loan and date table. Each table has no relationship between them.
* To make a relationship between two tables with the help of data modelling.
* I drag and drop the date column from date table to the issued_date of the finance_loan table
* It forms one to many relationship
* Date which is the primary key in date table becomes a foriegn key for the finance_loan table

# KPI's - Summary

* Now switch to report view
* As per the requirment, I have created a kpi cards using DAX for the following below
  - Total Loan Application
  - Total Funded Amount
  - Total Amount Received
  - Average Interest Rate
  - Average Debt-to-Income (DTI)
* Each Card includes MTD and MoM (Time Intelligence using DAX)
* Then I have created a doghnut charts for Good vs Bad Loans extract from loan status
* Finally created the table for Loan Status

# Charts's - Overview

* In new tab of power bi, I have created a dashboard for chart requirements
* I have created Area, Shape map, Doughnut, Line and Tree Map charts for Month Trend, State Address, Term, Employee length, Purpose and Ownership
* Each charts are dynamically changed based on
  - Total Loan Applications
  - Total Funded Amount
  - Total Amount Recieved

# Details

* This is the final dashboart of this project
* Create new tab in power bi for detail
* This dasboard contains a table of content for
  - Id
  - Purpose
  - Ownership
  - Grade Sub Grade
  - Issue Date
  - Total Funded Amount
  - Total Amount Received
  - Interest Rate
  - Installment

  # Finall Process

  * Create a header "Bank Loan Report | page name" for each page based on page name
  * Crate a side bar which consists of
    - Navigation buttons for Summary, Overview and Details
    - Filters for
      - Filter for fields (exclude for summary and details)
      - Filter for state
      - Filter for grade
      - Good vs Bad Loan
    

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/2be3176f-e6f3-4fd8-8592-c829536a6aa5" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/9e68643c-db0d-4d24-b872-4cb255865c86" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/dc7861c4-a795-4ddc-9a19-efcf71570ebe" />

