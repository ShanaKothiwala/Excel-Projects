# Excel-Projects
DA Practice Work
# 🚲 Bike Buyers Sales Analysis

An Excel-based analysis of a bike retailer's customer data, exploring who buys bikes and why. The workbook combines raw customer records with PivotTables and a dashboard of charts to surface patterns in income, commute distance, and age.

## 📁 Project Contents

| File | Description |
|------|-------------|
| `Bikes_Sales_Data.xlsx` | Source workbook containing the raw dataset, PivotTables, and dashboard |

The workbook has two sheets:

- **Bike Buyers Data** — 1,026 customer records with 14 fields
- **Pivot Table , Dashboard** — PivotTables and charts summarizing the data

## 📊 Dataset

Each row represents one customer, with the following fields:

| Column | Description |
|---|---|
| `ID` | Unique customer identifier |
| `Marital Status` | Married / Single |
| `Gender` | Male / Female |
| `Income` | Annual income |
| `Children` | Number of children |
| `Education` | Highest education level attained |
| `Occupation` | Job category |
| `Home Owner` | Yes / No |
| `Cars` | Number of cars owned |
| `Commute Distance` | Distance range to work |
| `Region` | Geographic region |
| `Age` | Customer age |
| `Age Brackets` | Age grouped into brackets (Young / Middle Age / Old) |
| `Purchased Bike` | Whether the customer purchased a bike (Yes / No) |

## 📈 Dashboard

The dashboard sheet includes three PivotChart visualizations built from the raw data:

1. **Average Income Per Purchase** — average income broken down by gender and purchase outcome
2. **Customer Commute** — bike purchase trends across commute distance ranges
3. **Customer Age Group** — bike purchase counts across age brackets

These charts are designed to help identify which customer segments (by income, commute, and age) are most likely to purchase a bike.

## ⭐ Important

**Pivot table and Dashboard are in the same sheet, as the Google Sheets slicer doesn't work if the pivot table and dashboard are in different sheets.**
