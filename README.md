# Vanguard AB testing

## Overview

This project involves analyzing client behavior and demographics in an online process by using Hypothesis Testing. The analysis is performed using Python and Jupyter Notebook. The information found during this analysis is visualized through using Tableau. 

## Data

The data used in this project comes from several CSV files, including `df_final_demo.txt`, `df_final_experiment_clients.txt`, `df_final_web_data_pt_1.txt`, `df_final_web_data_pt_2.txt`

## Analysis

The analysis includes the following steps:

1. **Data Cleaning and Preparation**: The data from the CSV files is loaded into pandas DataFrames and cleaned.

2. **Demographics Analysis**: The primary clients using the online process are identified, and their characteristics (such as age and client status) are analyzed.

3. **Client Behavior Analysis**: The behavior of clients during the online process is analyzed. This includes looking at the completion rate, the average time spent on each step, and the error rates.

4. **Hypothesis Testing**: Several hypotheses are tested, including whether there is a significant difference in age group distribution based on the variation column of `client_info`, and whether the average duration per step differs between control and test groups.

## Results

The results of the analysis and hypothesis testing are presented in the Jupyter Notebook and the visualization of these analysis are presented through Tableau. Result are also saved in csv file including `average_total.csv`, `confirm_rate.csv`, `duration_total.csv`, `error_rate_per_step.csv`, and `result_df.csv`.


## Files

- `Project2.ipynb`: The Jupyter Notebook containing the analysis.
- `README`: This file, providing an overview of the project.
- `average_total.csv`: This file provided and compare Average Duration Customers spent on each steps of the proccess
- `confirm_rate.csv`: This file provided and compare Confirm Rate of Customers seperating by their Age Group and their Role in the test
- `duration_total.csv`: This file provided and compare Duration each Customers spent on each steps of the test
- `error_rate_per_step.csv`: This file provided and compare number of Errors that customer faced spent on each steps of the test based on their Role in the test
- `result_df.csv`: This file provided and compare the overall KPIs that were used to compare the two group (Control and Test), including `completion_rate`,`error_rate`,`easy_success_rate`,`avg_duration_step`,`count`


**Presentation**
[Google Slide](https://docs.google.com/presentation/d/1IPHWxKpB7MLiGPrA37Z9vrTbxNYbdTQoBFnrYyi0Ybo/edit?usp=sharing)

**Tableau Story**
[Tableau Story](https://public.tableau.com/app/profile/hoang.le.duc/viz/Book1_17176249007780/Dashboard5)
## How to Run

To run the analysis, open `Project2.ipynb` in Jupyter Notebook and run all cells.

