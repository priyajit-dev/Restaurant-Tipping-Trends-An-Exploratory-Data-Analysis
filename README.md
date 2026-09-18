# Restaurant Tipping Trends: Exploratory Data Analysis

## Overview
This project explores customer tipping behaviors and restaurant revenue trends using the classic `tips` dataset. Through data cleaning, feature engineering, and exploratory data analysis (EDA), this project uncovers actionable insights regarding how party size, time of day, and customer smoking status impact gratuity rates.

## Technologies Used
* **Python**
* **Pandas** (Data cleaning, manipulation, and grouped aggregations)
* **Matplotlib** (Data visualization)
* **Jupyter Notebook**

## Dataset
The analysis is based on the `tips.csv` dataset (available via the Seaborn data repository), which contains 244 records of restaurant bills, tip amounts, customer demographics, party sizes, and dining times.

## Key Insights
* **Revenue vs. Tip Rates:** While weekends (Saturday and Sunday) drive the vast majority of the restaurant's total revenue, Friday actually yields the highest average tip percentage from customers.
* **The Party Size Effect:** There is a distinct downward trend in tip percentages as group sizes get larger. Solo diners and couples tend to leave proportionally larger tips than parties of 5 or 6.
* **Customer Habits:** The time of day has a minor impact, with lunch patrons tipping slightly higher percentages than dinner patrons. Meanwhile, a customer's smoking status does not drastically change their median tip percentage, though smokers tend to have slightly more unpredictable tipping habits.

## Repository Structure
* `tips_eda.ipynb` : The main Jupyter Notebook containing the code, analysis, and visualizations.
* `README.md` : Project overview and findings.

## How to Run
1. Clone this repository to your local machine.
2. Ensure you have Python installed along with the required libraries:
   ```bash
   pip install pandas matplotlib numpy
