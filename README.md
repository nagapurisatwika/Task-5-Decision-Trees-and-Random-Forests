# Task-5-Decision-Trees-and-Random-Forests.
To learn how Decision Trees and Random Forests work for classification, analyze performance, visualize trees, and check feature importance.

### Steps I Followed:
1. Imported Required Libraries:
Used pandas, numpy, matplotlib, and sklearn for modeling, plotting, and evaluating classification results.

2. Loaded the Iris Dataset:
I used the built-in `load_iris()` from sklearn, which gave me both features and target labels for flower classification.

3. Explored the Dataset:
Checked the first few rows and printed the target class names just to understand what we’re working with.

4. Split the Data:
Split the data into 70% training and 30% testing using `train_test_split()` to evaluate our models properly.

5. Trained a Decision Tree Classifier:
Used `DecisionTreeClassifier` with `max_depth=3` to avoid overfitting and trained it on the training set.

6. Visualized the Tree:
Plotted the decision tree using `plot_tree()` to understand how the model splits the data step by step.

7. Evaluated the Decision Tree:
Made predictions on test data, checked accuracy, and printed the classification report to see performance.

8. Trained a Random Forest Model:
Used `RandomForestClassifier` with 100 trees to improve accuracy using ensemble learning.

9. Checked Feature Importance:
Plotted the most important features using a horizontal bar chart to know which features affect predictions most.

10. Performed Cross-Validation:
Used 5-fold cross-validation for both models to see how stable their accuracy is across different data splits.

