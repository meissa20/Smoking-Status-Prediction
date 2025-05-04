# Smoking Status Prediction

## 📄 Project Overview
This project aims to predict an individual's smoking status using bio-signal data through a machine learning pipeline. The system integrates **data analysis, feature engineering, ensemble learning methods, and hyperparameter tuning** to build a robust predictive model.

## 🎯 Objectives
- Perform **univariate, bivariate, and multivariate analysis** to explore relationships in the dataset
- Apply **feature engineering** (normalization, outlier removal, feature creation) to improve model input quality
- Train and evaluate models using **Bagging, Boosting, and Random Forest** ensemble methods
- Optimize model performance via **Grid Search** and **Randomized Search** hyperparameter tuning
- Deliver a predictive system with the best evaluation metrics

## 🗂️ Project Structure
```
├── Exploratory_Analysis.ipynb            # Notebook for raw data exploration
├── Explanatory_Analysis.ipynb            # Clean notebook with key insights and visuals
├── Model_Training_And_Ensemble.ipynb     # Notebook for training models and ensembles
├── your_data                             # Contains dataset and generated variations
├── modified_data                         # Dataset After Variations
├── README.md                             # Project description and instructions
```

## 📝 Key Features
- 10+ features analyzed for their predictive relevance
- Visualizations created using **Matplotlib, Seaborn, Plotly**
- Feature engineering with **normalization (MinMax, Z-score), outlier removal, and feature selection**
- Ensemble models: **Bagging, Boosting, Random Forest**
- Hyperparameter tuning with **GridSearchCV** and **RandomizedSearchCV**

## 🧩 Requirements
The following Python packages are required for this project:

```
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
jupyter
```

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Open `Exploratory_Analysis.ipynb` in Jupyter Notebook and run cells
3. Repeat for `Explanatory_Analysis.ipynb` and `Model_Training_And_Ensemble.ipynb`
