# Quality & Safety Data Join

## Overview

This project integrated Quality Engineering claim and installation data with Product Safety incident data to develop an interactive Looker Studio dashboard. The dashboard aimed to proactively identify potential safety issues by comparing claim rates across both data sets. Additionally, it leveraged installation data to calculate claim rates for product safety, a capability that was previously unavailable.

## Tools
- Python (Pandas, SQLite3) for Data Analysis
- Looker Studio for Visualization - Dashboard Unavailable

## Code Overiew
| File Name | Description | Skills Demonstrated | 
|-----------|-------------|---------------------|
|[Quality & Safety Join](https://github.com/ddibara5/quality-data-join/blob/main/Quality%20%26%20Safety%20Join.ipynb)| This code utilized Pandas to import and clean data, reformatting fields for SQL processing. It also utilizes SQLite3 to add boolean columns, count relevant fields and perform summary calculations | Set Operators, Summary Statistics, Less Common Joins | 
| [Safety_Database_Automation](https://github.com/ddibara5/quality-data-join/blob/main/Safety_Database_Automation.ipynb) | This code focuses on automating the dashboard by making a RestAPI, utilizing client credentials to make a POST call for authorization, then a GET call to pull appropriate records. The results are then saved to a google sheet | RestAPI Authentication, Pandas, Gspread, Google Auth |
