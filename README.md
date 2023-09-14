# Crowd-Funding-Data-Analysis-Project

Project Overview:

Crowdfunding Data Analysis Project README

This README provides an overview of the steps and tasks completed in the Crowdfunding Data Analysis project. The project involved analyzing a dataset of 1,000 crowdfunding projects to uncover market trends and insights using Microsoft Excel.

Background
Crowdfunding platforms like Kickstarter and Indiegogo have gained popularity, but not all projects achieve their funding goals. The goal of this project was to organize and analyze a dataset of crowdfunding projects to discover hidden trends and draw conclusions about campaign success.

Steps and Tasks Completed
1. Data Organization and Setup
Created a new space called excel-challenge in Google Drive for storing project files.
Stored the Excel workbook (CrowdfundingBook.xlsx) in the dedicated space.
2. Data Visualization and Analysis
Outcome Visualization:

Used conditional formatting to color-code the outcome column for successful, failed, canceled, and live campaigns.
Percent Funded Calculation:

Created a new column called Percent Funded to calculate how much each campaign raised relative to its initial goal.
Applied conditional formatting with a three-color scale to visualize the Percent Funded data.
Average Donation Calculation:

Created a new column called Average Donation to calculate the average amount paid by project backers.
Category and Sub-Category Split:

Created two new columns, Parent Category and Sub-Category, by splitting the Category and Sub-Category column.
Category Analysis:

Created a new sheet with a pivot table to count the number of successful, failed, canceled, and live campaigns per category.
Generated a stacked column pivot chart for category analysis, filterable by country.
Sub-Category Analysis:

Created another sheet with a pivot table to count campaign outcomes per sub-category.
Generated a stacked column pivot chart for sub-category analysis, filterable by country and parent category.
Date Conversion:

Created Date Created Conversion and Date Ended Conversion columns to convert Unix timestamps in launched_at and deadline columns into Excel date formats.
Outcome Based on Launch Date:

Created a new sheet with a pivot table to analyze campaign outcomes based on launch date.
Generated a pivot chart line graph to visualize the relationship between launch date and outcomes, with filters for parent category and years.
3. Project Report
Prepared a report in Microsoft Word, addressing three key questions:
Three conclusions drawn from the data regarding crowdfunding campaigns.
Limitations of the dataset.
Proposed additional tables and graphs for deeper analysis.
4. Bonus Analysis
Goal Analysis:

Created a new sheet with columns for goal-related statistics (e.g., number of successful, failed, canceled projects).
Defined goal ranges and used COUNTIFS() to populate the columns.
Calculated the total projects and percentage for each goal range.
Created a line chart to visualize the relationship between goal amount and success/failure/cancellation rates.
Statistical Analysis:

Evaluated the number of backers for successful and unsuccessful campaigns.
Calculated statistics for both groups, including mean, median, minimum, maximum, variance, and standard deviation.
Determined whether mean or median summarizes the data more meaningfully.
Analyzed variability between successful and unsuccessful campaigns.
