# 🎓 Education & EdTech Data

A specialized collection of datasets focusing on **Educational Metrics and EdTech Performance**. These resources help in analyzing student progress, institutional efficiency, and digital learning engagement.

## 📚 Dataset Catalog & Use Cases

| Dataset | Research Category | Target Measurement | ML Focus |
| :--- | :--- | :--- | :--- |
| `education_attendance.csv` | Operations | Absence Patterns | RNN (Time-Series) |
| `education_college_admission.csv`| Enrollment | Probability of Adm. | Random Forest |
| `education_dropout_v2.csv` | Retention | Early Warning Sign | Gradient Boosting |
| `education_edtech_sub.csv` | Product | Platform Usage / ROI | K-Means |
| `education_exam_results_v2.csv` | Academic | Rank / Percentile | Linear Regression |
| `education_online_course.csv` | Engagement | Video Completion % | Sequence Mining |
| `education_scholarship.csv` | Finance | Funding Allocation | Optimization Modeling |
| `education_student_demo.csv` | Equity | Access Gap Stat. | ANOVA |
| `education_student_perf.csv` | Analytics | Final GPA Predictor | Multilayer Perceptron |
| `education_teacher_eval.csv` | Quality | Instructional Score | Sentiment Analysis |

## 🚀 EdTech Innovation Projects

1.  **Student Retention System:** Build a "Dropout Danger" dashboard that alerts counselors when a student's engagement in `online_course` and `attendance` starts to dip.
2.  **Personalized Learning Path:** Use `student_performance` to identify which specific concepts (features) a student struggles with and suggest adaptive modules.
3.  **Admissions Predictor:** Use `college_admission` data to build a tool that helps high-schoolers estimate their chances at various institutions.

## 🌟 Data Considerations

- **Privacy (FERPA):** In real EdTech projects, you must comply with student privacy laws. These datasets are synthetic for your safety.
- **Linguistic Bias:** When analyzing `teacher_eval` text, be aware of bias against non-native English speakers.
- **Intervention Effect:** Use the data to see if a specific `training` or `scholarship` actually improved `exam_results`.

---
*Part of the [Dataset Hub](../README.md) project.*
