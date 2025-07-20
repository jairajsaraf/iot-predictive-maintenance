# iot-predictive-maintenance
End-to-end ML demo predicting machine failures (AI4I 2020 dataset).

**Goal**: Predict machine failures using sensor data to enable proactive maintenance and reduce downtime.

## 1. Project Overview
- Dataset: [AI4I 2020 Predictive Maintenance](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance)
- Approach: Exploratory analysis → feature engineering → ML classification (baseline logistic regression & random forest)
- Tech: Python, pandas, scikit-learn, Jupyter

## 2. Quickstart
```bash
git clone https://github.com/<your-username>/predictive-maintenance.git
cd predictive-maintenance
pip install -r requirements.txt
jupyter notebook
# open notebooks/01_basic_eda_and_model.ipynb