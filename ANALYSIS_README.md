# Exploratory Data Analysis

This repository contains a comprehensive exploratory data analysis of the e-commerce dataset.

## Files

- **exploratory_data_analysis.ipynb**: Main Jupyter notebook containing the complete analysis
- **data/combined_ecommerce_data.csv**: Combined dataset joining users, events, and items data

## How to Use

1. Ensure you have Python and the required libraries installed:
   ```bash
   pip install jupyter pandas numpy matplotlib seaborn
   ```

2. Open the Jupyter notebook:
   ```bash
   jupyter notebook exploratory_data_analysis.ipynb
   ```

3. Run all cells to see the complete analysis, or run cells individually to explore specific aspects.

## Analysis Overview

The notebook answers the following key questions:

### 1. Which categories have the highest revenue?

**Top 3 Categories:**
- **Apparel**: $52,240 (1,592 purchases)
- **Bags**: $6,684 (239 purchases)
- **New**: $6,615 (471 purchases)

### 2. How do sales change over time?

- **Total Revenue**: $95,660
- **Total Transactions**: 4,903
- **Peak Sales Month**: November 2020
- Sales show clear patterns by:
  - Month (seasonal trends)
  - Day of week
  - Hour of day

## Features

The notebook includes:

- ✅ Data loading and exploration
- ✅ Data cleaning and preparation
- ✅ Joining multiple CSV files
- ✅ Revenue analysis by category
- ✅ Time-based sales analysis (monthly, daily, hourly)
- ✅ Device type performance analysis
- ✅ Top products identification
- ✅ Multiple visualizations (bar charts, line plots, pie charts)
- ✅ Summary of key findings
- ✅ Export of combined dataset

## Visualizations

The notebook generates various visualizations including:
- Revenue by category (bar charts and pie charts)
- Sales trends over time (line plots)
- Sales by day of week (bar charts)
- Sales by hour of day (line plots)
- Device type distribution (pie charts)
- Top products by revenue (horizontal bar chart)

## Dataset Information

The analysis uses three CSV files:
- **users.csv**: Customer profiles with lifetime value
- **events.csv**: User interaction events (purchases, cart additions, checkouts)
- **items.csv**: Product catalog with pricing and categorization

See `data/data_dictionary.md` for detailed column descriptions.
