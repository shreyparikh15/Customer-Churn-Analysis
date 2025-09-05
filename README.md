# Customer Churn Analysis

## Project Overview

This project provides an in-depth exploratory data analysis (EDA) of a customer churn dataset for a fictional telecom company. The primary objective is to identify key factors that contribute to customer churn. By understanding these drivers, the company can develop targeted strategies to improve customer retention.

The analysis is conducted using Python in a Jupyter Notebook (`Customer_churn(EDA).ipynb`) and leverages libraries such as Pandas for data manipulation, and Matplotlib and Seaborn for data visualization.

A detailed summary of the findings is available in the `Executive Summary_ Detailed Customer Churn Analysis.pdf` file.

## Key Questions Addressed

This analysis seeks to answer the following questions:
* What is the overall churn rate?
* How do customer demographics (gender, senior citizen status) impact churn?
* What is the relationship between contract type, payment method, and customer loyalty?
* How does customer tenure affect the likelihood of churn?
* Which specific services (e.g., Online Security, Tech Support) are most critical for customer retention?

## Key Findings

The analysis uncovered several significant patterns related to customer churn:

* **Overall Churn**: **26.54%** of the customer base has churned.
* **Contract Type**: Customers on **month-to-month contracts** have a significantly higher churn rate (**42.7%**) compared to those on one-year (**11.3%**) or two-year (**2.8%**) contracts.
* **Payment Method**: The churn rate for customers using **electronic checks** (**45.3%**) is nearly three times higher than for those using automatic payment methods (around 16%).
* **Key Services**: Customers without services like **Online Security** and **Tech Support** churn at a rate of over **41%**, whereas customers with these services have a much lower churn rate of approximately **15%**.
* **Tenure**: The highest concentration of churn occurs among new customers, especially those with a tenure of less than 10 months.
* **Senior Citizens**: Senior citizens exhibit a higher churn rate (**41.7%**) compared to non-senior citizens (**23.6%**).

## Files in this Repository

1.  **`Customer Churn.csv`**: The raw dataset used for the analysis. This file contains customer information, demographic data, and details about their subscribed services.
2.  **`Customer_churn(EDA).ipynb`**: A Jupyter Notebook containing the complete Python code for the exploratory data analysis. This includes data cleaning, analysis, and visualization steps.
3.  **`Executive Summary_ Detailed Customer Churn Analysis.pdf`**: A PDF document summarizing the key insights, numerical statistics, and recommendations derived from the analysis.

## How to Use This Repository

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/](https://github.com/)<your-username>/Customer-Churn-Analysis.git
    ```
2.  **Explore the Jupyter Notebook**:
    * Ensure you have Python and Jupyter Notebook installed.
    * Install the required libraries:
        ```bash
        pip install pandas matplotlib seaborn
        ```
    * Launch Jupyter Notebook and open `Customer_churn(EDA).ipynb` to view and run the analysis.
3.  **Review the Findings**:
    * For a quick overview of the results and actionable insights, please refer to the `Executive Summary_ Detailed Customer Churn Analysis.pdf`.

## Tools and Libraries Used

* **Python 3**
* **Pandas**: For data manipulation and analysis.
* **Matplotlib**: For creating static, animated, and interactive visualizations.
* **Seaborn**: For making statistical graphics.
* **Jupyter Notebook**: For interactive data analysis and visualization.
