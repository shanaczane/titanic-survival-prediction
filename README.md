# Titanic Survival Prediction

A data science project analyzing what factors influenced passenger survival on the Titanic, built as a recap of core Data Science 1 concepts (EDA, data cleaning, visualization, and classification modeling).

## Problem Statement

**Main Question:** Can we predict whether a passenger survived the Titanic disaster based on their characteristics?

**Sub-questions:**
- Did gender affect survival rate?
- Did passenger class (1st, 2nd, 3rd) affect survival?
- Did age play a role in survival?
- Did traveling with family help or hurt chances of survival?
- Did the fare paid correlate with survival?

**Type of Problem:** Binary classification (Survived = 1, Died = 0)

**Success Criteria:** A model that predicts survival with strong accuracy (~75-80%+).

## Dataset

- **Source:** [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data)
- **File used:** `train.csv`
- **Rows:** 891 passengers
- **Key columns:** `Survived`, `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`

## Project Structure

```
titanic-survival-prediction/
├── data/
│   └── train.csv
├── notebooks/
│   └── titanic_analysis.ipynb
├── visuals/
├── README.md
└── requirements.txt
```

## Process

1. Define the problem
2. Load and explore the data (EDA)
3. Clean the data (handle missing values, encode categories)
4. Visualize patterns
5. Feature engineering
6. Build a classification model
7. Evaluate model performance
8. Interpret results and conclude

## Tools Used

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Jupyter Notebook (VS Code)

## Key Findings

*(To be filled in after analysis)*

## Model Performance

*(To be filled in after modeling)*

## Conclusion

*(To be filled in after analysis — key insights, limitations, and next steps)*

## How to Run

```bash
pip install -r requirements.txt
```

Open `notebooks/titanic_analysis.ipynb` in VS Code and run cells in order.