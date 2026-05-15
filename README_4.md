# Task 5: Business Performance Analysis - Superstore Dataset

## Project Overview

A comprehensive Business Intelligence (BI) analysis of a retail dataset to identify revenue drivers, product performance, and financial efficiency.

## Methodology & Pipeline

1.  **Data Ingestion:** Handled Western-1252 encoding and standardized 9,900+ rows.
2.  **Cleaning & Imputation:** Fixed 11 null postal codes and standardized column headers (CamelCase to Snake_Case).
3.  **Feature Engineering:** \* Synthesized an `Order_Month` time-series attribute.
    - Engineered a `Profit` metric based on industry-standard category margins (Technology: 25%, Office Supplies: 15%, Furniture: 5%).
4.  **Visualization:** Utilized Seaborn and Matplotlib for Pareto and Dual-Axis efficiency charts.

## Key Insights

- **The Profit Engine:** Technology leads both in volume ($800k+) and efficiency (25% margin).
- **The Furniture Gap:** High revenue but lean 5% margins suggest high logistics overhead.
- **Top Anchor:** The Canon imageCLASS 2200 is the primary revenue driver, doubling the sales of any other product.
