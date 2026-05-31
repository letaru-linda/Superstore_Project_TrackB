Project Overview
This project focuses on analyzing four years of international retail sales data (2011–2014) from the Global Superstore dataset. The dataset tracks approximately 51,000 transaction records across 147 countries and 3 distinct product categories (Furniture, Office Supplies, and Technology). As part of DA JAN 2026 Group 4, our team cleaned, modeled, and visualized this data using Microsoft Excel and Tableau to find hidden operational bottlenecks, track seasonal purchasing trends, and deliver actionable business recommendations to improve profitability.

Core Analytics Findings

1. Global Sales Trajectory & Seasonality
   The Holiday Rush: Transaction volumes consistently peak during the 4th Quarter (October, November, and December) due to holiday shopping behaviors.

Market Breakdown: The Asia-Pacific (APAC) region serves as the primary driver of absolute gross revenue and volume, followed closely by Europe and the United States. 2. The Discount Correlation Danger Zone
Margin Impact: While the Technology category generates the largest absolute profit dollars, heavy promotions on smaller sub-categories cause severe margin drops.

The 40% Threshold: Data modeling proves that whenever order discounts exceed 40% (Discount > 0.4), the company almost universally sustains a net loss on the transaction.  
 3. Supply Chain & Logistics ConstraintsFulfillment Flags: Cross-referencing order priorities with shipping speeds exposed delays where premium "Same Day" choices failed to ship on day zero.

Peak Bottlenecks: Delays are highly concentrated during the Q4 volume surge, indicating warehouse congestion and carrier capacity limits.

Technical Implementations
Microsoft Excel (Data Cleaning & Modeling)
Power Query Pipeline: Executed 20 critical ETL steps including row-duplicate elimination, whitespace trimming, and type casting.

Advanced Formulas: Built dynamic financial lookups and summary metrics using conditional logic arrays (SUMIFS, COUNTIFS, AVERAGEIFS, MAXIFS, INDEX-MATCH, and nested IF statements).

Interactive Dashboard: Assembled visual KPI cards, dynamic trend lines, and cross-filtered pivot slicers linked to master data ranges.

Strategic Recommendations

1. Enforce System Discount Caps: Hardcode system boundaries in the ordering pipeline to block sales users from using discounts higher than 20% without explicit regional manager sign-off.

2. Expand Holiday Supply Chains: Onboard temporary logistics staff and distribution capacity early in Q3 to handle the predictable, recurring Q4 volume spike without breaking service SLAs.

3. Prune Unprofitable Sub-Categories: Restructure pricing tiers or drop underperforming, margin-negative products flagged in our visual treemaps.
