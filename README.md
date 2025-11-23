# Retail Strategy & Analytics Project 

#### 🚧 WORK IN PROGRESS 🚧

## Table of Contents
* [Project Overview](#project-overview)
* [Data](#data)
* [Project Roadmap](#project-roadmap)
* [Tools & Skills](#tools--skills)
* [Repository Structure](#repository-structure)
* [Data Privacy](#data-privacy)
* [Acknowledgement](#acknowledgement)

## Project Overview

Goal: To analyze customer transaction data and evaluate the financial impact of new store layouts for the Category Manager.

This project simulates a real-world engagement where I act as a data analyst helping a retailer optimize their sales strategy. It moves from initial data cleaning to statistical experimentation (A/B testing) and finally to commercial reporting.

## Data 
The analysis is based on the following simulated datasets provided by the internship program:

1. Transaction Data (QVI_transaction_data.xlsx)  

    Rows: ~264,836 records  

    Key Variables: `DATE`, `STORE_NBR`, `LYLTY_CARD_NBR`, `TXN_ID`, `PROD_NAME`, `PROD_QTY`, `TOT_SALES`  

    Context: Detailed records of individual customer purchases, focusing on chip/snack categories.  

2. Customer Data (QVI_purchase_behaviour.csv)  

    Rows: ~72,637 records  

    Key Variables: `LYLTY_CARD_NBR`, `LIFESTAGE` (e.g., Young Singles/Couples), `PREMIUM_CUSTOMER` (e.g., Budget, Mainstream).  

    Context: Demographic details used for segmenting customers into groups for behavioral analysis.

## Project Roadmap

I am currently working through the following three distinct modules:

#### Task 1: Data Preparation & Customer Analytics

[x] Data Cleaning: Identifying inconsistencies in transaction records.

[x] Segmentation: Grouping customers based on purchasing behavior.

[x] Visualization: identifying initial sales drivers and trends.

#### Task 2: Experimentation (Uplift Testing)

[ ] Benchmark Selection: Choosing control stores that match trial stores.

[ ] Statistical Analysis: Comparing sales performance between Trial and Control groups.

[ ] Impact Assessment: Calculating the specific revenue uplift from the new layout.

#### Task 3: Commercial Application

[ ] Reporting: Structuring findings using the "Pyramid Principle".

[ ] Recommendations: Translating data into actionable business advice for the Category Manager.

## Tools & Skills

* Language: R (focusing on tidyverse and ggplot2)

#### Key Concepts: 
* Customer Segmentation
* A/B Testing & Control Store Selection
* Pyramid Principle Communication
* Data Visualization

## Repository Structure

The code is organized by task to mirror the project workflow:

```
├── data/         
├── task1_prep_and_analysis/    
│   ├── 01_qt1.html              # Download file and open in browser
│   └── 02_qt1.Rmd               # Standard R markdown file
├── task2_uplift_testing/       
│   ├── 01_
│   └── 02_
├── task3_reporting/            
└── README.md                  
```

## Data Privacy

This project uses a simulated dataset provided by the virtual internship program. No actual proprietary client data is included.

---

## Acknowledgement

This project was made with the help of Quantium's virtual internship in Forage, and added to my portfolio to demonstrate full-cycle analytics skills using R. Thank you to Quantium for this fantastic learning opportunity.

* [Forage Link](https://www.theforage.com/simulations/quantium/data-analytics-rqkb)
* [Quantium](https://quantium.com/)

