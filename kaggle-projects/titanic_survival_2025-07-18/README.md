# Titanic - Machine Learning from Disaster
This is my **first Kaggle project**, exploring survival prediction on the Titanic using machine learning.
The project follows a step-by-step structure including data exploration, baseline modeling, and furture improvements.

## Project Structure
```
titanic_survival_2025-07-18/
├── data/                             # Raw competition data (ignored in .git)
├── notebooks/
│   ├── titanic_model_v1.ipynb        # First version model using TFDF + ensemble
│   └── eda_titanic_based_on_v1_submission_2025-07-21.ipynb  # EDA notebook based on v1 submission
├── output/
│   └── submission.csv                # Submission file
└── README.md                         # This file

```

## Progress so far (first attempt - July 2025 - based on Kaggle tutorial)  
- Baseline model (`titanic_model_v1.ipynb`) built using **TensorFlow Decision Forests (TFDF)**  
- Followed Kaggle's official tutorial as initial guidance  
- Implemented ensemble strategy (100 trees, varied seeds)  
- Successfully generated and submitted `submission.csv`  
- Kaggle Public Score: **0.80622**  
- Completed **EDA** based on the raw training date  

## Key EDA insights  
- **Sex** and **Pclass** are highly correlated with survival  
    → Females and 1st-class passengers had higher survival rates  
- **Fare** showed a moderate positive correlation  
    → Higher fare, slightly higher survival rate  
- **Age** showed weak correlation  
    → Younger passengers did not significantly influence survival  
- Results visualized using count plots, histograms, heatmaps, and bar plots  

## Next steps
- Add **feature engineering** (e.g., `Title`, `FamilySize`, `IsAlone`)  
- Try alternative models (XGBoost, RandomForest)  
- Apply validation techniques to avoid overfitting  
- Optimize model and improve Kaggle score  

## Notes
This project is based on the [Kaggle Titanic competition].  
The first attempt (`v1`) was built following the official tutorial.  
I will continue interating and deepening my understanding of ML through this case.  