# 🚀 Startup & SaaS Metrics

A collection of datasets tracking the growth, health, and operational performance of **Software-as-a-Service (SaaS) companies** and startups.

## 📊 Startup Performance Tracker

| File Name | Functional Area | North Star Metric | Recommended Model |
| :--- | :--- | :--- | :--- |
| `saas_customer_support.csv` | Ops | First Response Time | LDA Topic Modeling |
| `saas_feature_usage_v2.csv` | Product | Active Users (DAU) | Clustering (User Persona)|
| `saas_growth_metrics_v2.csv` | Finance | Rule of 40 (Growth+Profit) | Linear Projection |
| `saas_mrr_trends.csv` | Finance | Monthly Rec. Revenue | Prophet Forecasting |
| `saas_pricing_exp_v2.csv` | Revenue | ARPU (Avg Rev/User) | A/B Testing |
| `saas_subscription_churn.csv`| Retention | Churn Rate % | Survival Analysis |
| `saas_system_uptime_v2.csv` | DevOps | Error Rate % | Isolation Forest |
| `saas_trial_conversion.csv` | Growth | Trial-to-Paid % | Logistic Regression |
| `saas_user_activity_v2.csv` | Product | Feature Stickiness | Heatmap / Spearman Corr |
| `saas_user_cohort_v2.csv` | Growth | Retention per Cohort | Triangle Retention Map |

## 🚀 Startup Scale-up Projects

1.  **Churn Prediction Engine:** Build a model on `subscription_churn` that flags a user as "At Risk" as soon as their `user_activity` drops below a certain threshold.
2.  **Tier Transition Predictor:** Identify the "Moment of Value" (e.g., inviting 5 team members) that most often leads to a user upgrading from Free to Pro.
3.  **Pricing Elasticity Study:** Use `pricing_experiment` data to find the optimal subscription price that maximizes Total Revenue.

## 💡 SaaS Analytics Dictionary

- **LTV (Lifetime Value):** Average Revenue per User ÷ Churn Rate.
- **CAC (Customer Acquisition Cost):** Total Marketing Spend ÷ New Users.
- **Magic Number:** (Net New MRR × 12) ÷ Total S&M Spend. Aim for > 0.75.

---
*Part of the [Dataset Hub](../README.md) project.*
