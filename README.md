# 🛒 Blinkit Inventory & Profitability Analysis Dashboard
## 📌 Project Overview

This project presents a two-page Power BI dashboard analyzing inventory investment, profitability, and capital efficiency for Blinkit retail data.

The goal of this dashboard is not just reporting numbers, but enabling data-driven business decisions by combining revenue, profit, margin, and inventory utilization metrics.

### 🎯 Objectives
#### Page 1 – Executive Overview

-Provide a high-level summary of overall business performance.

Display:

-Total SKUs

-Total Inventory Value

-Total Revenue

-Total Profit

-Overall Margin %

-Compare inventory allocation vs profit contribution by category.

-Analyze weighted Category Margin % (Profit / Revenue).

Enable filtering by:

-Brand

-Shelf Life Days

-Support quick executive-level performance assessment.

#### Page 2 – Deep Dive Analysis

-Identify Top 10 profit-generating categories/products.

Introduce Inventory Efficiency metric:

-Inventory Efficiency = Profit / Inventory Value


Detect:

-High margin but low contribution segments

-Low efficiency categories (capital tied up with weak returns)

-Highlight low margin, high inventory areas needing optimization.

-Enable brand-level and shelf-life-based investigation.

## 📊 Key Metrics Used
### Metric	Formula
-Total Revenue	SUMX(price × max_stock_level)
-Total Profit	SUMX((mrp − price) × max_stock_level)
-Category Margin %	Profit / Revenue
-Inventory Efficiency	Profit / Inventory Value
-Total SKUs	DISTINCTCOUNT(product_id)


## 💡 Key Insights

-Pet Care drives highest total profit with strong inventory allocation.

-Instant & Frozen Food shows highest capital efficiency (40%), indicating strong ROI potential.

-Grocery & Staples underperforms in efficiency (~15%), suggesting pricing or inventory review.

-Margin alone is not enough — capital efficiency reveals deeper performance insights.

## 🛠 Tools Used

-Power BI

-DAX (SUMX, DIVIDE, DISTINCTCOUNT)

-Data Modeling

-Conditional Formatting & Visual Analytics

## 📈 Business Value

This dashboard helps management:

-Evaluate return on invested inventory.

-Identify expansion opportunities.

-Optimize pricing strategy.

-Improve capital allocation efficiency.

-Move from descriptive reporting to analytical insight.
