Titanic Survival Prediction
This project focuses on predicting the survival of passengers aboard the Titanic using machine learning. It explores various classification algorithms to determine which model most accurately identifies whether a passenger survived based on features like age, gender, and passenger class.
Project Overview
The objective is to perform a complete data science workflow, including:
* Data Cleaning: Handling missing values and ensuring data integrity.
* Feature Engineering: Processing numeric and categorical features for model compatibility.
* Model Comparison: Evaluating three different machine learning models:
   * Logistic Regression
   * Random Forest
   * Gradient Boosting
* Evaluation: Comparing models based on Accuracy, Precision, Recall, F1-score, and Training Time.
Results
After evaluating the models, Logistic Regression emerged as the best performing model for this dataset with an accuracy of approximately 79.33%.
Model Performance Metrics:
Model
	Accuracy
	Precision
	Recall
	F1-Score
	Logistic Regression
	0.793
	0.761
	0.703
	0.731
	Random Forest
	0.782
	0.743
	0.696
	0.720
	Gradient Boosting
	0.771
	0.718
	0.684
	0.701
	Project Structure
* main.py: The primary Python script containing the data processing and modeling logic.
* train (2).csv: The dataset used for training and validation.
* best_titanic_model.pkl: The serialized version of the best-performing model.
* requirements.txt: List of required libraries (Pandas, Scikit-Learn, etc.).
