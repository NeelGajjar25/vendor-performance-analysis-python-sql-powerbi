Business Problem

The objective of this analysis is to optimize inventory, vendor performance, and sales profitability in the retail/wholesale industry.

Key goals include:

Identifying underperforming brands

Determining top vendors for sales and gross profit

Evaluating bulk purchase advantages

Analyzing inventory turnover

Understanding profitability differences across vendors

📊 Exploratory Data Analysis Insights

Large dataset summarizing Vendor, Brand, Sales, Purchases, Profit, Inventory, and Pricing.

Key Issues Identified:

Presence of negative gross profits

Some products have zero sales

Extreme value outliers in freight cost, purchase price, and actual price

🔎 Initial Data Observations

Freight cost: Huge variation (0.09 → 257,032) indicates inconsistent logistics efficiency

Stock turnover: Ranges from 0 → 274, showing some products never sell while others sell rapidly

High turnover >1 suggests older inventory fulfilling customer demands

🧹 Data Filtering

To ensure analysis quality, records were filtered to remove:

Gross Profit ≤ 0

Profit Margin ≤ 0

Total Sales Quantity = 0

This removed loss-making or unsold products for clearer insights.

📈 Correlation Insights

Purchase Price vs Sales/Gross Profit: very weak (−0.012, −0.016)

Total Purchase Qty vs Total Sales Qty: extremely strong (0.999) → efficient turnover

Profit Margin vs Sales Price: negative (−0.179), indicates price increases reduce margins

Stock Turnover vs Profitability: weak negative correlation

🧪 Research Questions & Key Findings
1️⃣ Brands Needing Pricing or Promotional Adjustments

198 brands show low sales but high margins — ideal candidates for promotions or pricing strategy changes.

Example brands with high margins:

Santa Rita Organic

Debauchery Pnt Nr

Crown Royal Apple

Sauza Sparkling Wild Berry

2️⃣ Top Vendors by Contribution

Top 10 vendors → 65.34% of total purchases

Remaining vendors → only 34.7%
✔ This indicates dependency risk on a small vendor group.

3️⃣ Bulk Purchasing Impact on Cost Savings

Bulk buyers benefit with 72% lower unit cost:

Order Size	Unit Purchase Price
Small	43.77
Medium	17.89
Large	11.30

✔ Larger order quantities = strong cost advantages.

4️⃣ Vendors with Low Inventory Turnover

Slow-moving inventory results in:
🔴 $2.71M unsold stock value

Vendors with low turnover (examples):

Diageo North America – $980k unsold

Martignetti Companies – $928k unsold

Jim Beam Brands – $857k unsold

✔ These vendors increase holding costs and reduce cash flow.

5️⃣ Profit Margin Comparison: High vs Low Performers

Top vendors’ margin: ~31.17%

Low vendors’ margin: ~41.55%

✔ Low sellers have high margins but poor sales → pricing inefficiency
✔ High sellers have lower margins → need cost optimization

6️⃣ Statistical Validation

Hypothesis Test Outcome:

❌ Null hypothesis rejected

✔ Significant difference exists between top and low-performing vendors

Implication:
→ Low-performing vendor margins can be optimized
→ High-volume vendors can reduce cost inefficiencies

📝 Further Recommendations

Diversify vendors to reduce dependency risks

Use bulk purchasing strategies to reduce unit cost

Address slow-moving inventory with promotional or clearance strategies

Improve vendor pricing strategies based on margin vs volume analysis

Optimize stock management to reduce storage cost
