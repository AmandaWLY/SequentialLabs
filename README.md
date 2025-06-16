# Sequential Labs – Crypto-FICO™ Dataset & Model Card  
[🌐 sequentiallabs.com](http://sequentiallabs.com/)  

## 📦 Dataset Overview
1. **Volume** – 1,200,000 loans · 2007-2018 · 47 features + 15 anonymised engineered factors.
2. **Source** – LendingClub public filings, Kaggle Credit-Score benchmark, partner-exchange snapshots.
3. **Compliance** – Fully de-identified under PIPEDA/GDPR guidelines.

## 🚀 Why It Matters
Traditional FICO misses 90 %+ of crypto-native users. Our blended data fills that void, unlocking under-served borrowers and new fee streams for exchanges.

## 🏗️ Data Collection & Cleaning
* Raw CSVs ingested via AWS Glue, schema unified, outlier-winsorised.
* Synthetic minority over-sampling (SMOTE) applied to cure class imbalance.
* Crypto linkage hashed & salted; zero PII leaves our servers.

## 📈 Benchmark Accuracy

| Model                                          | AUC      | KS       | F1       |
| ---------------------------------------------- | -------- | -------- | -------- |
| **Sequential XGB-SHAP**                        | **0.92** | **0.68** | **0.87** |
| Public RF baseline                             | 0.88     | 0.59     | 0.71     |
| |          |          |          |

## ☎️ Contact
Questions, partnerships, media: research@sequentiallabs.com
