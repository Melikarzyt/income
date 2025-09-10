📌 Income Prediction using Decision Tree

📖 Project Overview

This project focuses on predicting whether an individual earns more than $50,000 per year based on demographic and work-related attributes from the U.S. Census dataset. The main objective is to build a machine learning model that can effectively identify high-income individuals.
We chose a Decision Tree Classifier as the primary algorithm due to its interpretability and ability to handle both categorical and numerical features. Model performance was measured using the F1-score, with special emphasis on the high-income class (>50K).

⸻

✅ Tasks Completed
	•	Data Exploration: Inspected dataset structure, checked data types, and ensured no missing values remained untreated.
	•	Data Cleaning:
	•	Removed irrelevant or non-informative columns such as fnlwgt.
	•	Replaced ambiguous entries (?) in categorical columns with the most frequent value.
	•	Encoding: Converted categorical features into numerical values using LabelEncoder.
	•	Feature Engineering:
	•	Created new features such as capital_diff (capital gain minus capital loss).
	•	Introduced a binary feature is_over_40_hours to capture work-hour intensity.
	•	Model Training: Trained a Decision Tree Classifier with tuned hyperparameters (max_depth, min_samples_split, min_samples_leaf, and criterion).
	•	Model Evaluation:
	•	Generated a classification report on the training data.
	•	Focused on F1-score for the >50K class, achieving 0.69, which indicates reasonable predictive power for identifying high-income individuals.
	•	Submission File: Created a clean, single-column CSV file containing predictions on the test set for external evaluation.
