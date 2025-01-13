# Credit Card Usage Analysis

## Overview
This project analyzes credit card usage patterns among customers, focusing on demographic factors and their influence on credit card behavior. The analysis employs various techniques, including data cleaning, exploratory data analysis (EDA), and statistical analysis.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Analysis Techniques](#analysis-techniques)
  - [Data Cleaning](#data-cleaning)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Statistical Analysis](#statistical-analysis)
  - [Visualizations](#visualizations)
- [Conclusions](#conclusions)

## Installation
To run this project, you need Python 3.x and the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scipy
```

## Usage
Clone this repository:

```bash
git clone <repository-url>
cd credit-card-usage-analysis
```

Load the dataset in Jupyter Notebook or any Python environment:

```python
import pandas as pd
df = pd.read_csv('path_to_your_dataset.csv')
```

## Analysis Techniques

### Data Cleaning
Data cleaning ensures data quality and reliability for analysis. Key steps include:

- Removing unnecessary columns.
- Checking for duplicates.
- Renaming columns for clarity.
- Normalizing text and column names.
- Handling missing values through imputation.
- Converting data types for efficient analysis.

### Summary Statistics
### Months Inactive
- **Average**: 2.3 months  
- **Standard Deviation**: 1.01 months  
- **Median**: 2 months  
- **Insight**: Most customers are inactive for about 2 months. However, significant variation suggests the need for strategies to re-engage customers inactive for longer periods.

### Total Transaction Count
- **Average**: 64 transactions  
- **Standard Deviation**: 23 transactions  
- **Median**: 67 transactions  
- **Insight**: Customers average 64 transactions, with notable variation in engagement levels. This can help tailor personalized marketing efforts.

### Revolving Balance
- **Average**: $1,162.81  
- **Standard Deviation**: $814.99  
- **Median**: $1,276.00  
- **Insight**: Customers maintain an average revolving balance of $1,162.81, with significant variability. Financial management tools could assist customers in managing balances more effectively.

### Available Credit
- **Average**: $7,469.14  
- **Standard Deviation**: $9,090.69  
- **Median**: $3,474.00  
- **Insight**: A wide range in available credit suggests diverse financial situations. Insights can inform credit limit adjustments and personalized offers.

### Amount Change Q4 to Q1
- **Average**: 0.76  
- **Standard Deviation**: 0.22  
- **Median**: 0.736  
- **Insight**: An average spending increase of 0.76 between quarters highlights trends in behavior, enabling adjustments to marketing strategies.

These statistics provide valuable insights into customer behavior, helping to inform strategies for enhancing engagement and satisfaction.

## Analysis & Visualization

### Age Distribution of Customers
The histogram shows that customers aged **45-50** hold the most credit cards, while **25-30** year-olds have the least. This indicates a significant middle-aged customer base and suggests targeting marketing strategies toward them.

### Churn Rates by Demographics
Customers earning **under $40k** are more likely to churn, while those making **over $120k** tend to stay. Additionally, **17%** of female customers churn compared to **14%** of males, highlighting the need for tailored retention strategies.

### Credit Limit by Education Level
The box plot reveals that credit limits generally increase with higher education levels. Customers with lower education may pose higher risks, suggesting the need for cautious credit assessments.

### Card Type Distribution
The pie chart shows the **'Blue'** card is the most popular, held by **93.18%** of customers. This information is crucial for product development and marketing focus.

### Credit Limit vs. Utilization Ratio
The scatter plot indicates a reverse correlation: higher credit limits often lead to lower utilization ratios, suggesting responsible financial management among those customers.

### Tenure Months and Spending
A positive correlation exists between tenure months and total transaction amounts, indicating that longer-term customers tend to spend more, driven by trust and possibly increased credit limits.

## Conclusion
Key findings include:
- Middle-aged individuals are primary credit card users.
- Lower-income customers are more likely to churn, especially females.
- Higher education levels correlate with higher credit limits.
- Basic card types are most popular among customers.
- Responsible usage is indicated by lower utilization ratios among high-limit customers.

These insights can enhance marketing strategies and customer engagement efforts.
