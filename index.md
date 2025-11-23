---
layout: page
title: "Cyclistic Bike-Share Case Study"
---

## About this project

This repository contains my capstone project for the Google Data Analytics Professional Certificate.  
I analyzed historical trip data from the Cyclistic (Divvy) bike-share program to understand how **casual riders** and **annual members** use the service differently. The goal is to support a marketing strategy focused on converting casual riders into annual members.

The work was done in **R** and includes data cleaning, exploratory analysis, visualization, and business recommendations.

---

## Key questions

- How do casual riders and annual members use Cyclistic bikes differently?
- When do they ride (weekdays vs weekends)?
- How long do their trips last?
- What usage patterns can inform marketing decisions?

---

## Main findings

- Casual riders take **longer trips** on average (about 36.5 minutes) compared with members (about 11.4 minutes).
- Casual riders use the service **mostly on weekends**, especially Saturdays and Sundays.
- Members ride **mainly on weekdays**, which suggests commuting or regular transport.
- Casual ride duration increases significantly on weekends, which points to leisure/tourism behaviour.

These patterns reveal two clear rider profiles:  
**weekend leisure users** and **weekday commuters**.

---

## Visuals

Some of the visualizations produced in R:

![Average ride duration](/cyclistic-case-study/images/RplotAvgRide.png)

![Average ride duration by day of week](/cyclistic-case-study/images/RplotAvgRide.png)

![Member vs casual ride length](/cyclistic-case-study/images/RplotMemberVsCasual.png)

![Number of rides by day of week](/cyclistic-case-study/images/RplotRidesByDay.png)

---

## Reports

If you prefer a written summary, you can download the PDFs here:

- **Final report (PDF)**  
  https://github.com/dpf-tech/cyclistic-case-study/raw/main/Cyclistic_Report_Capstone_Project.pdf

- **Executive summary (PDF)**  
  https://github.com/dpf-tech/cyclistic-case-study/raw/main/GH_Cyclistic_Summary_Report.pdf

---

## Repository structure

- `R/` – R scripts for data cleaning, analysis, and visualization  
- `images/` – exported plots used in the report and on this page  
- `Cyclistic_Report_Capstone_Project.pdf` – full written report  
- `GH_Cyclistic_Summary_Report.pdf` – one-page executive summary  
- `README.md` – project description and technical details

You can view the full code and files in the GitHub repository:

https://github.com/dpf-tech/cyclistic-case-study
