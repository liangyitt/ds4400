# ds4400 machine learning prediction

### Project Overview
This project involves analyzing match data from the game **League of Legends** with the goal of predicting match outcomes using machine learning classification methods.

### Data Preparation & Exploratory Data Analysis (EDA)
- The dataset comprises purely numerical data with no missing values, thus requiring minimal preprocessing.
- The classes (win/loss) are balanced approximately at a 50-50 ratio, eliminating concerns about class imbalance.

### Tools and Libraries
- Utilized essential Python data science libraries including `pandas`, `numpy`, `seaborn`, and `matplotlib`.
- Employed machine learning frameworks such as `scikit-learn` and `XGBoost`.

### Models and Methodology
Multiple classification algorithms were implemented and compared:
- **Logistic Regression**
- **Random Forest Classifier**
- **XGBoost Classifier**
- **Gaussian Naive Bayes**

Hyperparameter optimization was conducted via `GridSearchCV`, and the model performances were validated through cross-validation to ensure robustness and generalization.

### Model Evaluation & Interpretability
Models were evaluated using metrics such as Accuracy, Classification Reports, and Confusion Matrices. Additionally, the importance of individual features was analyzed using the Permutation Importance method, enhancing interpretability and insights from the results.
