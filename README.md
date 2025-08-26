# ABC Company Employee Data Analysis Project

This repository contains a comprehensive analysis of employee data from ABC Company, aiming to provide insights into various aspects of their workforce. The project involves data preprocessing, performing specific analytical tasks, visualizing the findings, and deriving key insights.

## Project Overview

The primary goal of this project is to analyze a dataset consisting of 458 rows and 9 columns, detailing information about employees across different teams within ABC Company. The analysis addresses several key questions related to employee distribution, positions, age groups, salary expenditure, and potential correlations.

## Dataset

The dataset used for this analysis is a Google Sheet. Due to limitations in direct linking within a README, please find the dataset (e.g., `employee_data.csv` or `employee_data.xlsx`) included in this repository.

## Preprocessing Steps

Before proceeding with the analysis, the following preprocessing step was performed:

*   **Height Column Correction**: The "height" column, likely containing inconsistent or placeholder data, was replaced with randomly generated numbers between 150 and 180 (inclusive). This ensures data consistency and integrity for any potential future analyses involving employee height.

## Analysis Tasks

The following analytical tasks were carried out to extract meaningful information from the dataset:

1.  **Employee Distribution by Team**: Determined the number of employees in each team and calculated their percentage split relative to the total workforce.
2.  **Employee Segregation by Position**: Identified the count of employees holding different positions within the company.
3.  **Predominant Age Group**: Segmented employees into defined age groups and identified the age group with the highest number of employees.
4.  **Highest Salary Expenditure**: Calculated the total salary expenditure for each team and each position to identify which team and position incur the highest salary costs.
5.  **Age-Salary Correlation**: Investigated if there is a statistical correlation between an employee's age and their salary, and quantified this relationship.

## Graphical Representations

For each analysis task, appropriate visualizations were created to effectively present the findings. These visualizations are crucial for understanding trends and patterns at a glance. Common types of plots used include:

*   **Bar Charts**: For showing distributions (e.g., employees per team, employees per position, age group distribution).
*   **Pie Charts**: (Optional, but useful for percentage splits) For visualizing the percentage distribution of employees across teams.
*   **Scatter Plots**: For visualizing the relationship between two continuous variables (e.g., Age vs. Salary) and observing correlation.

## Insights Gained (Data Story)

Based on the analysis, here are some potential key trends, patterns, and correlations observed in the dataset:

*   **Team Composition**: The distribution of employees across teams might reveal whether the company is heavily reliant on a few large teams or if the workforce is evenly spread. The percentage split highlights the proportional size of each department.
*   **Organizational Structure**: The segregation by position offers a clear picture of the company's hierarchy and the number of individuals in different roles (e.g., a large number of entry-level positions versus managerial roles).
*   **Workforce Demographics**: Identifying the predominant age group can provide insights into the general age demographic of the company, which can have implications for training, benefits, and long-term planning.
*   **Cost Centers**: Understanding which teams and positions have the highest salary expenditure is critical for budgeting and resource allocation. It might indicate where the company's significant operational costs lie.
*   **Age-Salary Relationship**: The correlation analysis between age and salary can reveal if there's a positive trend (older employees tend to earn more), a negative trend (less common), or no significant relationship. This could shed light on career progression paths and salary structures within the company.

## Additional Information

*   The code for this project is written in Python, primarily utilizing libraries such as `pandas` for data manipulation, `matplotlib.pyplot` and `seaborn` for data visualization.
*   The project is structured within a Jupyter Notebook to allow for a step-by-step execution and clear presentation of code, outputs, and visualizations.
*   Further analysis could involve exploring other correlations (e.g., position vs. salary, team vs. height), or deeper dives into individual team performances if relevant data were available.



