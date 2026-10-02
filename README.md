# Usage Patterns & Loyalty: Telecom Churn Analytics 📞📉
This project moves beyond simply tracking churn as a descriptive outcome to building an actionable, data-driven customer retention system. Utilizing an end-to-end analytics pipeline, the project cleans telecom subscriber records, profiles usage behavior, segments risk tiers, and estimates individual-level churn probabilities to protect recurring revenue.

### ❓ The Business Problem & Dataset
The business is facing an overall **customer churn rate of 26.5%**, which has directly resulted in **$139,000 in lost revenue** (representing **30.5% of total revenue**). Analyzing a Kaggle-sourced dataset of **7,043 customers across 22 behavioral dimensions**, this project isolates exactly where financial loss is concentrated and delivers a prioritized decision framework for proactive customer intervention.

### 🔍 Explored Questions
To transform raw customer metrics into an actionable retention system, this project structured its exploratory data analysis (EDA) and modeling around six core business questions:

1. **Risk Identification:** Which specific customer cohorts are statistically most likely to leave the platform?
2. **Feature Impact:** How does the adoption depth of individual add-on services directly influence customer loyalty?
3. **Engagement Correlation:** Does higher engagement (subscribing to multiple service categories) lead to stronger, long-term retention?
4. **Lifecycle Mapping:** What exact role does customer tenure play in predicting steady, predictable subscription behavior?
5. **Financial Risk Concentration:** Which specific user segments contribute the absolute most to our $139K recurring revenue loss?
6. **Resource Optimization:** How can the marketing and success teams effectively prioritize high-risk, high-value accounts to maximize retention ROI?

### 🚀 Key Analytics Insights & Business Impact
* **Critical Churn Window:** Over **53% of all customer churn occurs within the first 12 months** of onboarding, indicating that early lifecycle engagement is the highest priority timeline.
* **True Loyalty Drivers:** Controlling for engagement depth proves that not all additions are equal; adding high-impact services like **Online Security and Tech Support decreases individual customer churn by up to 26%**.
* **High-Risk Segment Concentration:** Customers on Month-to-Month contracts who have low tenure (≤12 months) and high monthly charges make up a "New & Vulnerable" segment with a massive **70% churn rate**, accounting for **49% of all lost revenue** ($68,301).
* **Data-Driven Intervention:** Designed a priority matrix matching individual risk probabilities (derived via Gradient Boosting and Logistic Regression) with Monthly Charges to target retention spend strictly on high-revenue-at-risk accounts.
