# 👥 HR & Workforce Analytics

A collection of datasets dedicated to **Human Resources and Talent Management**. These resources focus on the employee lifecycle—from recruitment to retention and performance.

## 🏢 People Analytics Catalog

| File Name | Domain | Primary Target | Potential Value |
| :--- | :--- | :--- | :--- |
| `hr_employee_attendance.csv` | Operations | Absenteeism rate. | LSTM Time-series |
| `hr_employee_attrition.csv` | Retention | `attrition` (Yes/No). | XGBoost / SVM |
| `hr_employee_demographics.csv` | DEI | Diversity distribution. | Descriptive Stats |
| `hr_employee_engagement.csv` | Culture | Engagement Score (1-10). | Correlation Matrix |
| `hr_employee_performance.csv` | Talent | Review Rating (1-5). | Support Vector Regr. |
| `hr_employee_salary.csv` | Total Rewards | Market Benchmarking. | Random Forest Regr. |
| `hr_employee_training.csv` | L&D | Skill Growth Index. | K-Nearest Neighbors |
| `hr_promotion_progression.csv` | Career | Time-to-Promotion. | Survival Analysis |
| `hr_recruitment_hiring.csv` | Talent Acq | Candidate Conversion %. | Decision Trees |
| `hr_workforce_planning.csv` | Strategy | Talent Gap / Surplus. | Linear Forecasting |

## 🚀 Workforce Transformation Projects

1.  **The Retention Shield:** Use the attrition dataset to identify which factors (Work-Life Balance, Pay, Manager) most drive employees to quit.
2.  **Pay Equity Audit:** Build a regression model to predict salary. If gender or race is a strong predictor, it signals a potential bias in the pay structure.
3.  **Hiring Success Predictor:** Use historic `recruitment_hiring` data to predict which sourcing channels (LinkedIn, Referral, Jobs Board) produce the longest-tenured hires.

## 📝 HR Analytics Best Practices

- **Bias Detection:** Always check your models for disparate impact on protected classes.
- **Narrative Data:** Combine engagement scores with sentiment from employee open-ended comments.
- **Lead vs. Lag:** Notice that `engagement` is a lead indicator for `attrition`. Build multi-stage models for better accuracy.

---
*Part of the [Dataset Hub](../README.md) project.*
