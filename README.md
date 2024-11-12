# pandas-challenge-1

## ChatGPT was used to assist with the coding and readme of this assignment

# E-Commerce Data Analysis with Pandas

This project is a data analysis challenge focused on exploring, transforming, and analyzing a fictional e-commerce dataset using Python's Pandas library. The dataset represents sales data from a fictional company, and the objective is to derive insights about top customers, popular product categories, and profit calculations.

## Table of Contents
- [Background](#background)
- [Assignment Requirements](#assignment-requirements)
- [Data Exploration](#data-exploration)
- [Data Transformation](#data-transformation)
- [Data Validation](#data-validation)
- [Data Summary and Analysis](#data-summary-and-analysis)
- [Conclusions](#conclusions)

## Background

Practical data analysis is an essential skill in data science, machine learning, and business intelligence. This project involves examining, cleaning, and transforming data to extract actionable insights. The analysis includes identifying top customers, calculating profits, and summarizing data in a structured format, preparing for complex data scenarios in future projects.

## Assignment Requirements

1. **Explore the Data**: Familiarize with the dataset by viewing column names, running basic statistics, and answering preliminary questions.
2. **Transform the Data**: Calculate various columns for each sales line, including:
   - Line subtotal
   - Shipping price (based on weight)
   - Total price (with sales tax)
   - Line cost
   - Line profit
3. **Validate Results**: Confirm calculations with known values for specific orders.
4. **Summarize and Analyze**: Identify top clients, compute totals, and format data for presentation.

## Data Exploration

This section covers data exploration tasks such as:
- **Viewing Column Names**: Quick inspection of column headers to understand the data structure.
- **Basic Statistics**: Using descriptive statistics to gather insights into numerical data.
- **Top Categories and Clients**: Identification of the top categories, subcategories, and clients based on frequency in the dataset.

## Data Transformation

Key data transformations include:
- **Subtotal Calculation**: `unit_price * qty`
- **Shipping Price Calculation**: Shipping rates vary based on weight thresholds.
- **Total Price with Tax**: Incorporates shipping and sales tax at 9.25%.
- **Line Cost and Profit**: Calculated as total cost per line and profit derived from `line_price - line_cost`.

## Data Validation

For quality control, specific order totals are compared to known values:
- **Order ID 2742071**: Expected total price = $152,811.89
- **Order ID 2173913**: Expected total price = $162,388.71
- **Order ID 6128929**: Expected total price = $923,441.25

## Data Summary and Analysis

The final analysis includes:
- **Top 5 Clients by Quantity**: Calculating spending for each of the top clients identified in Part 1.
- **Summary DataFrame**: Created to show total units purchased, shipping price, revenue, cost, and profit for each top client.
- **Currency Formatting**: Monetary values are converted to millions for clarity in presentation.

### Findings
The analysis highlights the significant contribution of the top 5 clients to the company’s overall revenue, with total revenue and profits in the millions. These insights can support targeted marketing and retention efforts for high-value clients.

## Conclusions

This challenge illustrates the data analysis workflow, from exploration and transformation to validation and summary. The insights derived from top customers and profitable categories provide valuable direction for business decisions. This foundational approach to data analysis will be applicable to more complex datasets in future projects.

---

## Getting Started

1. **Clone the Repository**: `git clone <repository-url>`
2. **Install Dependencies**: Ensure you have Pandas installed (`pip install pandas`).
3. **Run the Code**: Execute the notebook cells to perform the analysis.
4. **Verify Results**: Check calculations against known totals in Part 3 for accuracy.

## License

This project is licensed under the MIT License.
