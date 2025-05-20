# Mushroom-Dataset-Classification
This project uses a dataset of mushroom characteristics to build predictive models that classify whether a mushroom is edible or poisonous. It demonstrates skills in exploratory data analysis (EDA), categorical encoding, supervised learning, and model evaluation using various classification techniques.

Dataset Source: UCI Mushroom Dataset

Shape: 8124 rows × 22 features

Target variable: class (e for edible, p for poisonous)

All features are categorical (e.g. odor, gill-color, population, etc.)

Project Objectives
Clean and explore a fully categorical dataset

Visualise relationships between features and target class

Encode features using One-Hot Encoding for compatibility

Train and evaluate several classification models

Identify the best-performing model(s) based on accuracy and F1-score

 Tools & Libraries
Python (Jupyter Notebook)

pandas, seaborn, matplotlib

scikit-learn (Logistic Regression, Decision Tree, Random Forest, GaussianNB, KNN, SVM)

XGBoost

Models Used
-Logistic Regression	
-Decision Tree	
-Random Forest	
-Gaussian Naive Bayes	
-K-Nearest Neighbours	
-Support Vector Machine	
-XGBoost	

One-Hot Encoding was used to safely handle all categorical variables across models amd Label Encoding was applied to the target class.

Key Findings
Odor and spore-print-color were the most predictive features.

Most models performed very well due to the clean and balanced dataset.

Most of the models performed well with high evaluation metric scores.

Visualisation helped interpret how specific features (like bruises or stalk-shape) affect edibility.

Conclusion
This project demonstrates the full machine learning pipeline — from data cleaning and encoding to model comparison and interpretation. It also highlights the importance of using the right encoding technique (One-Hot) for fully categorical data to ensure model integrity.

