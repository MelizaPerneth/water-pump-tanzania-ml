# Water Pump Status Prediction — Tanzania

![Python](https://img.shields.io/badge/Python-3.x-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-green)
![LightGBM](https://img.shields.io/badge/LightGBM-brightgreen)

Machine learning project to predict...

Machine learning project to predict the operational status of water pumps across Tanzania, developed as part of the Master's program in Machine Learning at UCM.

The goal is to classify each water point into one of three categories:
- Functional
- Functional but needs repair
- Non functional

## Results
| Submission | Local Accuracy | Competition Score |
|------------|---------------|-------------------|
| Submission 1 | 0.8036 | 0.8143 |
| Submission 2 | 0.8057 | 0.8160 |
| Submission 3 | 0.8046 | 0.8140 |
| **Submission 4** | **0.8077** | **0.8179** |

Final ranking: **#2583** on DrivenData.

## Approach
- Exploratory data analysis (EDA)
- Feature engineering (geographic, temporal and interaction features)
- Class imbalance handling with SMOTE
- Models: Random Forest, XGBoost, LightGBM, Gradient Boosting
- Soft voting ensemble
- Pseudo-labeling (semi-supervised learning)

## Data
Dataset from the [DrivenData competition](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/).
Download the data directly from there and place the CSV files in the root folder.

## Requirements
```bash
pip install -r requirements.txt
```
