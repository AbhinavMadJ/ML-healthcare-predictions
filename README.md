# Machine Learning Projects – Healthcare Applications

This repository contains two machine learning projects in the healthcare domain.  
All details, methodology, and results are described below.


## Projects Implemented

### 1. Nutrient Intake vs Recommended Dietary Allowance (RDA)
**Objective:**  
Analyze an individual’s nutrient intake against standard RDA values to identify deficiencies or excesses.

**Approach:**  
- Collected nutrition data and mapped to RDA tables.
- Calculated percentage intake versus RDA for each nutrient.
- Visualized gaps using bar charts.

**Technologies:**  
Python, Pandas, NumPy, Matplotlib.


### 2. Sleep Cycle Analysis
**Objective:**  
Analyze sleep patterns to detect irregular or unhealthy cycles.

**Approach:**  
- Processed sleep datasets (sleep hours, quality metrics).
- Applied Local Outlier Factor (LOF) to detect anomalies in sleep patterns.
- Highlighted entries deviating from healthy cycles.

**Technologies:**  
Python, Scikit-learn (LOF), Pandas, Seaborn.

## Tech Stack
- Languages/Libraries: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Tools: Jupyter Notebook
- Techniques: Local Outlier Factor (LOF), data visualization, anomaly detection


## Results Summary
- Nutrient analysis flags nutrients below or above RDA and visualizes gaps.
- Sleep cycle analysis detects outliers in sleep patterns for further investigation.


## How to Run
1. Install Python 3 and Jupyter Notebook.
2. Install required libraries:
   ```
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
