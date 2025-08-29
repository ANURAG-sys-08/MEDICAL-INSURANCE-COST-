Medical Cost Prediction Project
An end-to-end machine learning project to predict medical insurance costs using regression models, feature engineering, and hyperparameter tuning. The final tuned XGBoost model achieved a top-tier R-squared score of approximately 0.88.

📝 Project Overview
This project builds a regression model to predict individual medical insurance costs based on attributes like age, BMI, and smoking status. The workflow involved data cleaning, advanced feature engineering (e.g., creating interaction terms like bmi_smoker), and training multiple models including Linear Regression, Random Forest, and XGBoost. The dataset used is the "Medical Cost Personal Datasets" from Kaggle.

📈 Results & Evaluation
Models were evaluated using the R-squared (R 

The feature importance plot from the final model confirms that smoking status is the single most predictive factor of medical costs.

🛠️ Technologies Used
Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, and Seaborn.

🏁 Conclusion
The final tuned XGBoost model is the champion, achieving an R-squared score of 0.878. This represents the maximum predictive power extractable from the given dataset.
