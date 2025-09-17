# NBA Machine Learning Analysis 🏀

This repository contains a machine learning project analyzing NBA player data and season statistics.  
The goal is to **build predictive models** and **explore patterns** in player performance using historical datasets.

---

## 📂 Repository structure
├── MLA_1.ipynb # Main Jupyter notebook (analysis & models)
├── player_data.csv # Dataset with player demographic/physical data
├── seasons_stats.csv # Dataset with per-season aggregated statistics
└── README.md # Project documentation

---

## 📊 Project overview
- **Dataset sources**:  
  - `player_data.csv`: player-level information (e.g. name, age, height, position).  
  - `seasons_stats.csv`: per-season performance statistics (e.g. points, assists, rebounds).  

- **Main goals**:  
  1. Clean and merge datasets into a single analysis-ready format.  
  2. Explore correlations and key performance indicators (KPIs).  
  3. Apply machine learning models to predict player outcomes (e.g., scoring averages, efficiency).  
  4. Visualize historical trends and player development.  

- **Techniques used**:  
  - Data cleaning & preprocessing (`pandas`, `numpy`)  
  - Feature engineering (e.g., ratios, normalized stats)  
  - Exploratory Data Analysis (EDA) with plots (`matplotlib`, `seaborn`)  
  - Machine Learning models (`scikit-learn`):
    - Logistic Regression
    - Decision Trees / Random Forest
    - Support Vector Machines (SVM)
  - Model evaluation: accuracy, precision, recall, F1-score

---

## 🚀 Quickstart
### 1. Clone the repository
```bash
git clone https://github.com/Diegotorrearecha/nba-ml-analysis.git
cd nba-ml-analysis
