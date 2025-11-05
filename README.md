# Customer Segmentation Analysis (RFM Model)

## Project Overview
This project performs Customer Segmentation using RFM (Recency, Frequency, Monetary) analysis to identify customer groups based on their purchasing behavior.
The goal is to help the company prioritize marketing strategies, improve customer retention, and increase revenue through data-driven insights.

---

## Business Objective
The main business questions addressed are:
1. Which customer segments generate the most revenue?
2. How can the company identify loyal vs. at-risk customers?
3. What marketing strategies can be tailored to each segment?

---

## Analytical Approach
| Step | Description |
|------|--------------|
| 1. Data Collection & Cleaning | Raw transaction data imported from CSV. Missing values and duplicates were handled in `data_clean`. |
| 2. Feature Engineering | Created RFM features (Recency, Frequency, Monetary) based on the latest transaction date. |
| 3. RFM Scoring | Scored customers on each dimension (1–5) and combined into a single RFM Score. |
| 4. Segmentation Mapping | Assigned segments such as Champions, Loyal, Potential Loyalists, Hibernating, At Risk, and New Customers. |
| 5. Dashboard Visualization | Built in Power BI to visualize revenue by segment, country, and top customers. |

---

## Key Insights
- Champions contribute the largest share of revenue (~60%) and have the highest order frequency.
- Potential Loyalists show promising behavior; targeted promotions could convert them into Champions.
- Hibernating and At Risk customers represent re-engagement opportunities through reactivation campaigns.
- The United Kingdom drives most sales, suggesting focused marketing could yield high ROI there.

---

## Recommendations
- Implement personalized loyalty programs for top-tier customers.
- Design email remarketing campaigns for at-risk segments.
- Introduce referral incentives to acquire new customers from existing loyal bases.
- Use geographic segmentation (by country) to optimize localized marketing budget allocation.

---

## Repository Structure
```
Customer_Segmentation/
│
├── data_raw/         # Original dataset
├── data_clean/       # Processed & cleaned data
├── notebooks/        # Python notebooks (EDA & RFM calculations)
├── dashboard/        # Power BI or Streamlit dashboard files
├── outputs/          # Processed CSVs / model exports
├── slides/           # Presentation slides for business stakeholders
└── images/           # Screenshots or plots for README/docs
```

---

## Tools & Technologies
- Python (Pandas, Numpy, Matplotlib, Seaborn)
- Power BI (Interactive dashboards)
- Jupyter Notebook / Google Colab
- Excel (Data preparation)
- GitHub (Version control)

---

## Deliverables
- Cleaned dataset
- RFM scoring table
- Power BI dashboard (3 pages: Overview, Market & Segment, Top Customers)
- Final presentation slides

---

## Results Summary
| Segment | % of Customers | % of Revenue | Suggested Strategy |
|----------|----------------|---------------|--------------------|
| Champions | 14% | 60% | Reward and retain |
| Potential Loyalists | 17% | 12% | Engage & upsell |
| Loyal | 13% | 9% | Maintain satisfaction |
| Hibernating | 25% | 8% | Reactivate with offers |
| At Risk | 20% | 7% | Personalized reactivation |
| New Customers | 11% | 4% | Welcome campaigns |

---

## Author
Hans Christian  
Bandung, Indonesia  
Marketing Designer & Aspiring Data Scientist  
Email: hans.dsda771@gmail.com  
LinkedIn: https://www.linkedin.com/in/hanschristian771/
