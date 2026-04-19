# ecommerce-regional-analysis
global-vs-regional-ecommerce-analysis
Ecommerce Customer & Revenue Segmentation: Global vs Regional Analysis
UK Retail Chain EDA (392K+ Transactions)
Cleaned, segmented, and business-ready insights from UCI Online Retail dataset.

# Business Questions Answered
Customer Geography — UK dominates (90%+ customers) but regions reveal hidden patterns

Shopping Behavior — Days with highest unique visitors

Revenue by Market — Germany volume vs Netherlands value

Top Products — Global vs regional best-sellers (POSTAGE, CAKESTANDS, LUNCH BOXES)

#  Key Findings
Metric	UK	Europe	Asia	Insight
Customers	3,921 (90%)	437 (10%)	27 (<1%)	UK bias confirmed — global = UK
Revenue	£8.3M (91%)	£817K (9%)	£35K (<1%)	Netherlands punches above Germany
Top Product	PAPER CRAFT (£168K)	POSTAGE (£67K)	REGENCY CAKESTAND (£8K)	Regional preferences matter
#  Data Cleaning Pipeline
text
Raw: 541,909 rows × 8 cols
↓ Remove missing CustomerID: 406,829 rows
↓ Remove cancelled invoices (C prefix): 397,924 rows  
↓ Remove duplicates: 392,732 clean rows
↓ Add: Revenue, Day-of-Week, Region mapping
Libraries: Pandas - Seaborn - Matplotlib - WordCloud

#  Business Recommendations
Stop treating "international" as one market — Europe alone has Germany (volume) vs Netherlands (value)

Stock regionally — UK loves PAPER CRAFT; Europe prefers lunch boxes & cake tins

Target Thursday-Friday — peak unique customer days globally and regionally

Watch shipping costs — POSTAGE dominates non-UK revenue

#  Tech Skills Demonstrated
Data Cleaning — Missing values, cancellations, duplicates, dtype conversion

Segmentation — Global vs regional views to avoid UK bias

Revenue Engineering — Quantity × UnitPrice + aggregation

Visualization — Bar charts, pie charts, scatter plots, word clouds

