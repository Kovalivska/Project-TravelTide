# TravelTide Analysis

**Project Description**
This project focuses on customer segmentation and perk optimization for TravelTide, a fast-growing e-booking startup. The goal is to improve customer retention by providing personalized rewards based on user behavior and engagement patterns.This project analyzes TravelTide's user engagement and performance metrics, leveraging data insights to improve platform functionality and user experience.

**Project Summary**

This repository contains an analysis of TravelTide’s user behavior and spending habits, leading to data-driven recommendations for perk assignments.

**Key Points and Insights:**

-  Customer Segmentation: K-Means clustering was applied to segment users based on demographics, travel frequency, and booking patterns. The segmentation allowed us to identify distinct user groups with varying levels of spending and engagement.

-  Booking Trends: The majority of users engage with the platform multiple times before completing a booking. Repeat visitors show a significantly higher conversion rate, reinforcing the importance of sustained engagement.

-  Preferred Perks: The analysis confirmed that users have distinct preferences for perks. Budget-conscious travelers favor discounts, while frequent flyers are more interested in priority services and upgrades.

-  Cancellation Behavior: A segment of users demonstrates a high cancellation rate, necessitating flexible booking options to reduce churn and enhance retention.

-  Spending Patterns: High-value users, particularly luxury travelers and business clients, tend to bundle hotel and flight bookings, making them ideal candidates for exclusive rewards and premium services.

-  Model Evaluation: Random Forest was used to assess the segmentation model’s effectiveness, confirming that user behavior and travel spending can reliably predict perk preferences.

-  Optimization Goal: The project aims to refine the perk assignment strategy to maximize retention and improve booking conversion rates through targeted, data-driven recommendations.

**Relevant Files:**

Data Science Project Report: Data Science Project Report_TravelTide(2).pdf

Jupyter Notebook: V_3_NewTravelTide (2).ipynb

Executive Summary: Executive_Summary_TravelTide.pdf

Project Presentation: TravelTideProjectPresentation (2).pptx

Raw Data: Row Data

Aggregated Data: agg_df (2).csv - This file contains preprocessed and aggregated data used for reproducing the results of the analysis.

Merged Data with Clusters: merged_with_clusters(2).csv - This final dataset includes customer clusters and assigned perks based on segmentation results.

Project Video: Video TravelTide1.mp4



## Installation
1. Clone the repository:

```bash
git clone [https://github.com/your-repo/traveltide-analysis.git](https://github.com/Kovalivska/Project-TravelTide.git)
```
2. Navigate to the project directory:

```bash
cd traveltide-analysis
```
3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the main script to perform the analysis:

```python
python v_3_newtraveltide.py

```
## Directory Structure

```python
traveltide-analysis/
│-- data/                # Contains raw and processed data
│-- scripts/             # Python scripts for analysis
│-- reports/             # Final reports and summaries
│-- V_3_NewTravelTide (2).ipynb  # Jupyter Notebook
│-- README.md            # Project documentation
│-- Data Science Project Report_TravelTide(2).pdf
│-- Executive_Summary_TravelTide.pdf
│-- TravelTideProjectPresentation (2).pptx
│-- Row Data/            # Contains raw data 
│-- agg_df (2).csv       
│-- merged_with_clusters(2).csv 
│-- Video TravelTide1.mp4
```
## Dependencies

Python 3.x

Pandas

NumPy

Matplotlib

Seaborn

Plotly

SciPy

Statsmodels

Scikit-learn

SQLAlchemy

Airportsdata

Geonamescache

Gapmap

Graphviz

IPython (for display functions)

## Example Usage
To install dependencies, run:
```python
pip install -r requirements.txt
```
