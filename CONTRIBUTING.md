# Contributing to Open Dataset Hub

First off, thank you for considering contributing to the Open Dataset Hub! It's people like you that make this a great resource for the community.

## 🛠️ How Can I Contribute?

### 1. Adding New Datasets
We are always looking for more realistic, synthetic datasets.
- **Rule 1:** Datasets MUST be synthetic or completely anonymized. No real PII.
- **Rule 2:** Datasets should be in CSV format.
- **Rule 3:** File naming: `category_datasetname_dataset_v3.csv`.
- **Rule 4:** One dataset per CSV.

### 2. Improving Documentation
Found a typo? Want to add more column descriptions to a category README? Pull requests are welcome!

### 3. Feature Engineering
If you have a script that adds derived features (e.g., calculating ROI from cost and revenue columns) to an existing dataset, please share it or the updated dataset.

## 🚀 Pull Request Process

1. Fork the repository and create your branch from `main`.
2. If you've added a dataset, ensure it follows the folder structure.
3. Update the category `README.md` if you added a new file.
4. Ensure no datetime overflow issues (e.g., dates in 2099 unless intentional).
5. Submit the PR with a clear description of what the dataset contains and its use case.

## 📝 Dataset Quality Checklist
- [ ] No dummy/placeholder columns (e.g., "column1", "test").
- [ ] Meaningful header names.
- [ ] Consistent data types within columns.
- [ ] At least 1000 rows (preferred) for "large" status.

---
*By contributing, you agree that your data will be released under the CC BY 4.0 License.*
