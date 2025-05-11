# 🚢 Titanic - Survival Prediction with ML

This project is part of my portfolio and focuses on predicting passenger survival using classification models.  
It was built around the classic Titanic dataset from Kaggle, and emphasizes feature selection, class balance, and interpretability.

## 🔍 Project Overview

- ✅ Performed EDA to explore relationships between features and survival
- ✅ Used **Cramér’s V** to assess correlation between categorical variables
- ✅ Engineered features such as `Title`, `Age Groups`, and `Fare Bins`
- ✅ Trained a **CatBoostClassifier** for its native handling of categorical features
- ✅ Evaluated model using **accuracy**, **F1-score**, and **confusion matrix**
- ✅ Tuned hyperparameters using **GridSearchCV**

## 📈 Techniques Used

- **CatBoost** with `class_weights` to address class imbalance
- **GridSearchCV** for hyperparameter tuning
- **Feature importance extraction** using `get_feature_importance()`
- Visualization of survival by group (e.g. by `Sex`, `Pclass`, `Embarked`)

## 🔜 Next Steps

- Add SHAP values for more detailed explainability
- Automate feature engineering pipeline
- Try ensemble stacking or compare with LightGBM and XGBoost
- Test model on imbalanced synthetic data

---

*Built with ❤️ by Victoria Cabrera*
