Titanic ML Project Guide
========================

Your uploaded dataset looks like a Titanic survival dataset.

Detected columns:
- PassengerId
- Survived
- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- FamilySize
- Embarked_C
- Embarked_Q
- Embarked_S

Project title idea:
"Passenger Survival Prediction Using Machine Learning"

Goal:
Predict whether a passenger survived (1) or not (0).

Suggested workflow:
1. Understand the dataset
2. Clean missing values
3. Select features and target
4. Split train/validation data
5. Train more than one model
6. Compare accuracy
7. Save the best model
8. Explain results in your project report

How to run:
1. Put this script and the CSV file in the same folder
2. Install packages:
   pip install pandas numpy scikit-learn joblib
3. Run:
   python titanic_project_training.py
