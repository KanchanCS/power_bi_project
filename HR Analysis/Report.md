# Power BI HR Analytics Dashboard

This Power BI project focuses on HR analytics, analyzing various HR-related metrics and visualizing them through interactive charts and graphs. The dataset used in this project contains HR data, including employee count, attrition count, job satisfaction ratings, education field, age group, gender, and department.

## Prerequisites

To view and interact with the Power BI dashboard, you need to have Power BI Desktop or Power BI Online installed on your computer.

## Getting Started

Follow these instructions to access and interact with the HR analytics dashboard:

1. Download Power BI Desktop from the official website and install it on your computer (if you don't have it already).
2. Download the Power BI project file from the repository or shared link.
3. Open Power BI Desktop and open the downloaded project file (.pbix).
4. If the dataset source has changed, you may need to update the dataset connection accordingly.

## Dashboard Features

The HR analytics dashboard contains various charts and graphs to analyze HR metrics and trends. Here's an overview of the dashboard's key features:

### Attrition Rate

- **Attrition Rate**: A measure calculated as `SUM('HR Data'[Attrition Count]) / SUM('HR Data'[Employee Count])`. It represents the percentage of employees who left the company.
- **Attrition Active**: A measure calculated as `SUM('HR Data'[Employee Count]) - SUM('HR Data'[Attrition Count])`. It represents the number of active employees (excluding those who left).

### Attrition Analysis

- **Attrition Count by Condition**: This chart is created using conditional columns. It shows the attrition count based on specific conditions.

### Department-wise Attrition

- **Pie Chart**: Visualizes attrition count in each department using a pie chart.

### Employee Age Group

- **Stacked Column Chart**: Represents the number of employees in each age group using a stacked column chart.

### Job Satisfaction

- **Matrix**: Displays job satisfaction ratings in a matrix format, allowing easy comparison of ratings.

### Education Field-wise Attrition

- **Stacked Bar Chart**: Shows attrition count based on different education fields using a stacked bar chart.

### Attrition Rate by Gender for Different Age Groups

- **Donut Chart**: Illustrates the attrition rate by gender for different age groups using a donut chart.
