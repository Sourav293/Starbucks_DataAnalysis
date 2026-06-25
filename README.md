# Starbucks_DataAnalysis
# Starbucks Beverage Insights Dashboard — Power BI

An interactive Power BI dashboard built on Starbucks beverage data, looking at calories, caffeine, sugar content, and how things differ across categories.

## Overview

This is a single-page Power BI report exploring nutritional and categorical patterns across Starbucks beverages. It's built from a single flat table (no relationship modeling needed since everything lives in one dataset), with KPI cards, trend charts, and ranking visuals tied together by slicers that filter the whole page at once.

## Key Features

- **KPI Cards** — Total Beverages, Average Sugar, Average Calories, Average Caffeine
- **Dynamic Slicers** — Beverage Prep and Protein Range filters update every visual on the page in real time
- **Average Calories by Beverage Category** — area chart showing calorie trends across categories
- **Beverage Category Distribution** — donut chart showing the proportional split of categories
- **Average Caffeine by Category** — horizontal bar chart comparing caffeine levels
- **Top 5 Highest Caffeine Beverages** — Top-N filtered bar chart, dynamically recalculated based on active slicer selections

## Tools & Skills Used

- **Power BI Desktop** — report building, visuals, slicers
- **DAX** — measures for average calories, caffeine, and sugar by category; Top-N filtering logic
- **Power Query** — basic data cleaning before loading into the report

## Dataset

The dataset has Starbucks beverage details — calories, caffeine, sugar, protein, category, and prep type. I got it from a YouTube Power BI tutorial I was following while building this.

## Repository Contents

```
├── starbucks_dashboard.pbix     # Power BI report file
├── starbucks_data.csv           # Source dataset
└── README.md
```

## How to View

1. Download `starbucks_dashboard.pbix`
2. Open with [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads) (free)
3. Data will load automatically from the embedded model

## What I Learned

This was a good exercise in connecting slicers, filters, and DAX measures so they all interact correctly across every chart on the page — getting Top-N filtering to recalculate properly depending on what's selected took a bit of trial and error. Also helped me get more comfortable structuring DAX measures so they stay reusable across different visuals instead of writing one-off calculations everywhere.

## Author

**Sourav**
[GitHub](https://github.com/Sourav293)
