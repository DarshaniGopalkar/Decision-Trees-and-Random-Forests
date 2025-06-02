🌳 Heart Disease Classification — Decision Trees & Random Forest
This project is part of an AI & ML Internship focused on implementing tree-based models for binary classification using the Heart Disease dataset.

📄 Objective
To build and evaluate classification models (Decision Tree and Random Forest) to predict the presence of heart disease based on patient medical attributes.

📋 Steps:
1. Loaded the dataset (heart.csv) using Pandas
2. Explored and cleaned the data (checked for null values, data types)
3. Split the data into features (X) and target (y)
4. Performed train-test split (80% training, 20% testing)
5. Trained a Decision Tree Classifier
6. Visualized the decision tree using plot_tree
7. Controlled overfitting by setting max_depth (pruning)
8. Trained a Random Forest Classifier
9. Compared model performance using accuracy and classification report
10. Interpreted feature importances using a bar plot
11. Evaluated model using cross-validation (5-fold)

📊 Results:
Model	Accuracy
Decision Tree	~ 81%
Pruned Tree (depth=4)	~ 85%
Random Forest	~ 90%
Cross-Validation Avg (RF)	~ 88-91%

🛠 Tools Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn

✅ Files
heart.csv – Heart Disease dataset
Task_05.ipynb – Python notebook with code and analysis
README.md – Project summary
