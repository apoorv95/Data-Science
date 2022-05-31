# Anomaly Detection
• Objective - The objective of the project is to determine whether a designing intrusion is anomaly or normal using machine learning technique.
• Methodology – Random Forest, Association Rule



Dataset
• How many features – 40(39 input, 1 output)
• Size of the dataset – 2,439KB with 22544 Rows and 40 Columns
• Multiple files – No multiple files
• What kind of data – numerical and categorical
• Balanced or imbalanced – Partially Imbalance
• Distribution of Training set, validation set, testing set –
75% - training data, 25% testing data
• Missing data and Preprocessing challenges –
1. No missing values
2. 2 duplicate data is present
3. Outliers in 35 features/columns (0.21% - 24%)


Feature Engineering Techniques
• Features removed – 5 features (land, root_shell, su_attempted, num_shells, num_outbound_cmds)
• Feature creation - None
• Feature ranking – Yes
• Class imbalance treatment – No (not needed)
• Feature Selection Method –
1. Variance Threshold Method
2. Select K-Best Method


Methodology
• Classifiers – Random Forest, Association Rules (Apriori Algorithm) – These two algorithms were given to use
• Ensemble pipeline - None
• Other models considered – None.
• Hyper-parameter tuning
1. Random Forest hyper parameter tuning using Grid Search Cross Validation
Parameters:
a. Max depth
b. Minimum sample leaf
c. Minimum samples split.
2. Association Rule
a. Protocol type
b. Service
c. Flag
d. Class



Results
• Table for the evaluation metric for each ML technique used
• Plot of the curves
• Conclusion
The Random Forest model performed very well and gave 100% output for both train and test data. It is not over fitting.


