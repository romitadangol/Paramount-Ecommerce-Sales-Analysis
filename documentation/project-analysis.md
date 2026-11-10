
# Project Analysis & Methodology

## 1. Project Background

Paramount Stationery & Sports is an e-commerce retail business selling stationery, school supplies, art materials, sports products, toys, and home organization items through Daraz.

This project analyzes historical sales and financial transaction data to understand business performance and identify useful insights for decision-making.

## 2. Data Sources

The project uses two primary datasets:

- Daraz order export containing product-level sales records.
- Daraz income statement export containing sales-related financial transactions, fees, refunds, and adjustments.

**Reporting Period:** April 2022 – October 2026

**Currency:** Nepalese Rupees (NPR)

## 3. Data Preparation

The following preparation steps were performed:

- Reviewed and structured the raw datasets.
- Standardized transaction dates for monthly analysis.
- Categorized products into relevant business categories.
- Used lookup formulas to map products to their respective categories.
- Handled transactions without associated product names separately.
- Checked the consistency of product-level and monthly sales totals.

## 4. Analytical Approach

### Product Performance Analysis

Analyzed product-level sales and recorded financial transaction amounts to identify high-performing products.

### Category Performance Analysis

Grouped products into business categories and compared their sales contributions.

### Monthly Sales Analysis

Aggregated sales by month to identify sales peaks, low-performing months, and overall trends.

### Financial Transaction Analysis

Examined commissions, payment fees, handling fees, shipping charges, refunds, incentives, and other recorded income-statement entries.

## 5. Key Findings

- Total recorded product sales: NPR 1,673,400.
- Total recorded net income-statement transactions: NPR 1,373,120.64.
- Highest monthly sales: NPR 61,717 in November 2022.
- Lowest monthly sales: NPR 10,215 in May 2022.
- Paints & Art Supplies was the highest-contributing product category in the product-level sales analysis.

## 6. Data Validation

The monthly product sales total was reconciled against the product-level financial summary.

Both reports returned NPR 1,673,400, confirming consistency between the two analytical views.

The monthly income-statement transaction total was also reconciled against the source income-statement data.

## 7. Limitations

- The analysis is based on historical Daraz transaction records.
- Product-level financial summaries include only transactions associated with identifiable products.
- Certain income-statement fees and adjustments are not linked to individual products.
- Recorded net income-statement transactions should not be interpreted as final seller payout or business profit.

## 8. Tools Used

- Microsoft Excel
- XLOOKUP
- SUMIF / SUMIFS
- SORT / UNIQUE
- Excel Tables
- Data cleaning and transformation
- Data aggregation and visualization
- Executive dashboard development
