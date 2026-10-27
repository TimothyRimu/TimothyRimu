# Hi, I'm Timothy Rimu 👋

**Data analyst and data scientist** based in Nakuru, Kenya, open to remote roles. I turn messy, real-world data into analysis people can trust, and I report what did *not* work as plainly as what did.

Certified through **AFRICDSA** (Certified Data Scientist/Analyst programme). Before data, I built Phaneros Consulting Services, so I'm used to answering business questions, not just fitting models.

## Featured projects

| Project | Question | Result |
|---|---|---|
| [**Kenya bank profitability**](https://github.com/TimothyRimu/Kenya_Bank_Analysis) | What drives bank profitability, and does ML beat a regression? | Cost-to-income is the one robust driver. A fixed-effects regression (MAE 0.46) beat XGBoost (0.70) out of time, on 84 bank-years. |
| [**INX employee performance**](https://github.com/TimothyRimu/INX-Future-Inc) ([live app](https://inx-future-inc.streamlit.app)) | Which factors drive performance, and can it be predicted? | ~92% honest accuracy vs 72.8% baseline; corrected a 98.7% leaky result; pre-hire prediction is no better than chance. |
| [**iFood campaign targeting**](https://github.com/TimothyRimu/ifood-campaign-targeting) ([live app](https://ifood-campaign-targeting.streamlit.app)) | Who should the next marketing campaign target? | Mass mailing loses 1.31 per customer; a logistic model (AUC 0.90) targeting the top 18% earns +0.59. |
| [**Loan approval**](https://github.com/TimothyRimu/loan-approval-prediction) | What drives loan decisions? | Credit history alone gives 80.9% accuracy; the other inputs add nothing to accuracy. |
| [**Diabetes risk**](https://github.com/TimothyRimu/diabetes) ([live app](https://diabetes-diabetes.streamlit.app)) | How much does a data leak flatter a model? | Outcome-based imputation inflated tree models from 76% to 88%; honest score 76-77%. |
| [**Apple stock forecasting**](https://github.com/TimothyRimu/apple-stock-forecasting) | Can ML forecast the next day's move? | No: R² ≈ 0 out of sample; the original 0.9999 was a leak. |
| [**Power BI dashboards**](https://github.com/TimothyRimu/power-bi-dashboards) | Marketing and financial reporting | iFood campaign overview and a sales/profit dashboard. |

## Skills

**Python** (pandas, scikit-learn, statsmodels, XGBoost, SHAP) · **Statistics** (panel regression, bootstrap inference, cross-validation) · **Visualisation** (matplotlib, Power BI) · **Apps** (Streamlit) · **Git & reproducible notebooks**

## How I work

- Evaluate out of sample, against a simple baseline, before claiming a model is good.
- Keep data leakage out: resampling and tuning happen inside training folds only.
- Ship something usable: every project has a README, pinned dependencies and a notebook that re-runs end to end.

📫 Find me on GitHub at [@TimothyRimu](https://github.com/TimothyRimu)
