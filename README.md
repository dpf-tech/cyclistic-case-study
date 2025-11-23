# Cyclistic Bike-Share Case Study
Google Data Analytics Professional Certificate – Capstone Project

## Overview
This project explores bike-share usage patterns to understand how casual riders and annual members use Cyclistic bikes differently.  
The objective is to support a marketing strategy focused on converting casual riders into annual members.

## Skills Demonstrated
- R programming (dplyr, ggplot2, lubridate, janitor)
- Data cleaning and preparation
- Exploratory data analysis
- Data visualization
- Business reporting and communication

## Data
Data was provided by Motivate International Inc.

Datasets:
- Divvy Trips 2019 Q1
- Divvy Trips 2020 Q1

## Data Cleaning
Data cleaning and preparation were performed in R using tidyverse packages.  
Key steps included:
- Standardizing inconsistent column names
- Converting text timestamps to datetime format
- Creating `ride_length` and `day_of_week` variables
- Removing invalid trips (negative or longer than 24 hours)
- Merging datasets (combined size ~792,000 records)

## Key Findings

1. **Casual riders take longer rides**  
   - Casual: 36.5 minutes  
   - Member: 11.4 minutes  

2. **Casual riders use the service more on weekends**  
   - Particularly on Saturdays and Sundays  

3. **Members ride mainly on weekdays**  
   - Consistent with commuter usage  

4. **Casual ride duration increases significantly on weekends**  
   - Indicates leisure or tourism-driven behavior

## Visualizations
- Average ride duration by day of the week  
- Member vs. casual ride length  
- Number of rides by day of the week  

(Plots available in the `images/` folder.)

## Recommendations
- Offer weekend-focused membership promotions
- Use experience-based marketing aimed at leisure riders
- Expand partnerships with employers to increase weekday member usage

## Challenges and Solutions
- Column name inconsistencies between years → resolved with `rename()`
- Timestamp fields imported as text → corrected with `ymd_hms()`
- `ride_id` format mismatch → converted to character
- tidyverse dependency issues on Linux → resolved by installing packages individually
- Removed invalid trips (>24 hours or negative duration)

## Reports
Final versions of the project reports are available below:

- **Final Report (PDF)**  
  https://github.com/dpf-tech/cyclistic-case-study/raw/main/Cyclistic_Report_Capstone_Project.pdf

- **Executive Summary (PDF)**  
  https://github.com/dpf-tech/cyclistic-case-study/raw/main/GH_Cyclistic_Summary_Report.pdf
