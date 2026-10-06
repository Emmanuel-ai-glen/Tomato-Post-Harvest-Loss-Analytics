# Tomato Post-Harvest Loss Analytics | Excel

## Overview

This project analyzes a simulated farmer-level dataset to investigate
patterns in tomato post-harvest loss rates.

The project demonstrates an end-to-end Excel analytics workflow:

Problem Definition → Data Understanding → Data Quality →
Cleaning → Derived Variables → Exploratory Analysis →
Comparative Analysis → Visualization → Dashboard → Insights

> Note: The dataset is simulated and was created for analytical
> learning and portfolio demonstration. It is not real survey data.

## Dashboard Preview

[![Tomato Post-Harvest Loss Analytics Dashboard](https://github.com/Emmanuel-ai-glen/Tomato-Post-Harvest-Loss-Analytics/blob/main/excell.png)](https://github.com/Emmanuel-ai-glen/Tomato-Post-Harvest-Loss-Analytics/blob/main/excell.png)

## Problem

Tomato post-harvest losses can reduce the quantity and value of
produce available for sale.

The project investigates which farmer and post-harvest conditions
are associated with higher observed loss rates.

## Objective

To analyze farmer-level data and identify patterns in post-harvest
loss rates across:

- Storage method
- Transport method
- Distance to market
- Days before sale

## Dataset

The dataset contains 150 farmer records.

[📊 View/Download the simulated Excel dataset](https://github.com/Emmanuel-ai-glen/Tomato-Post-Harvest-Loss-Analytics/blob/main/tomato_post_harvest_loss_messy_simulated.xlsx)

### Unit of Analysis

One farmer record.

### Variables

- Farmer_ID
- Harvest_kg
- Quantity_Lost_kg
- Quantity_Sold_kg
- Storage_Method
- Transport_Method
- Distance_to_Market_km
- Days_Before_Sale
- Selling_Price_TZS_per_kg

## Data Quality

The raw dataset was intentionally designed to contain data-quality
issues.

Checks included:

- Missing values
- Duplicate Farmer IDs
- Inconsistent categorical labels
- Numeric/data-type inconsistencies
- Invalid/impossible values
- Logical consistency
- Potential outliers

Initial missing-value counts included:

- Harvest: 3
- Quantity Lost: 5
- Quantity Sold: 1
- Storage Method: 0
- Transport Method: 0
- Distance to Market: 4
- Days Before Sale: 2
- Selling Price: 3

No duplicate Farmer IDs were identified.

## Data Preparation

The project included:

- Cleaning numeric values
- Standardizing categorical labels
- Creating Loss Rate
- Creating distance categories
- Creating sale-delay categories
- Creating exploratory loss categories
- Validating logical relationships
- Investigating potential outliers

For Quantity Lost:

- Q1 = 47 kg
- Q3 = 103.5 kg
- IQR = 56.5 kg
- Upper boundary = 188.25 kg
- 16 potential high-loss observations were identified

Potential outliers were not automatically removed.

## Analysis

The analysis used:

- Descriptive statistics
- Mean
- Median
- Minimum
- Maximum
- Standard deviation
- Distribution analysis
- IQR-based outlier analysis
- PivotTables
- Comparative analysis

Loss rates were compared across:

- Storage method
- Distance to market
- Transport method
- Days before sale

## Key Findings

### Overall

Average loss rate: **14.50%**

### Storage

- Cold storage: 12.92%
- Improved storage: 10.59%
- No storage: 17.97%
- Traditional storage: 13.48%

### Distance

- Near: 11.54%
- Medium distance: 15.17%
- Far: 18.57%

### Transport

- Bicycle: 15.98%
- Motor cycle: 15.85%
- Other: 13.68%
- Pick up: 12.04%
- Truck: 15.61%

### Days Before Sale

- Quick sale: 10.87%
- Moderate delay: 14.62%
- Long delay: 16.93%

These findings represent observed associations/patterns in the
simulated dataset and should not be interpreted as causal effects.

## Dashboard

An interactive Excel dashboard was created containing:

- KPI cards
- Comparative visualizations
- PivotTables
- Slicers

The dashboard allows users to explore loss-rate patterns across
different post-harvest conditions.

## Insights

The analysis showed higher observed loss rates among:

- Farmers farther from markets
- Farmers without storage
- Farmers experiencing longer delays before sale

These patterns identify areas that may deserve further investigation
and stakeholder attention.

## Recommendations

The analysis supports further attention to:

- Collection and transport coordination for farmers farther from markets
- Access to improved storage
- Coordination between farmers, buyers and transport providers to reduce
  unnecessary sale delays

These recommendations should be treated as practical areas for
investigation rather than causal conclusions.

## Tools

- Microsoft Excel

## Skills Demonstrated

- Data Cleaning
- Data Quality Validation
- Exploratory Data Analysis
- Descriptive Statistics
- Outlier Analysis
- Comparative Analysis
- PivotTables
- Data Visualization
- Dashboard Development
- Analytical Problem Solving
- Insight Communication
