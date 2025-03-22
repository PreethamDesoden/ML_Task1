# Decision Tree Classification 🌳

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : PREETHAM B

*INTERN ID* : CT12WM72

*DOMAIN* : MACHINE LEARNING 

*DURATION* : 12 WEEKS

*MENTOR* : NEELA SANTOSH 

## Introduction

A Decision Tree is a supervised machine learning algorithm commonly used for classification and regression tasks. It is a tree-like structure where each internal node represents a feature (attribute), each branch represents a decision rule, and each leaf node represents an outcome or class label. The goal of this task was to build, visualize, and analyze a decision tree model using Scikit-learn to classify or predict outcomes based on a chosen dataset

## Objectives

The primary objectives of this task were:

- Implement a Decision Tree model using the Scikit-learn library.

- Perform data preprocessing to clean and prepare the dataset.

- Train the model and analyze its performance.

- Visualize the Decision Tree to understand how the model makes predictions.

- Evaluate the model using performance metrics such as accuracy, precision, recall, and confusion matrix.

- Save the results in a Jupyter Notebook with detailed code, analysis, and visualization. 

## Dataset Used

The dataset used for this task is 'iris' dataset. It contained multiple features and a target variable to be classified. The dataset was cleaned and processed to ensure accurate model predictions. Some key aspects of the dataset included:

1. Feature Selection: Identifying relevant columns for training.

2. Handling Missing Values: Replacing or removing incomplete data.

3. Encoding Categorical Variables: Converting text data into numerical format using techniques like one-hot encoding or label encoding.

4. Data Splitting: Dividing the dataset into training and testing subsets.

## Implementation Steps

### 1. Data Preprocessing

- Before training the Decision Tree model, we performed the following preprocessing steps:

- Loaded the dataset into a Pandas DataFrame.

- Explored the dataset to understand its structure and contents.

- Handled missing values by either imputing or removing incomplete rows.

- Converted categorical features into numerical format using encoding techniques.

- Split the data into training (80%) and testing (20%) sets using train_test_split() from Scikit-learn.

### 2. Model Implementation

- Imported the necessary libraries such as DecisionTreeClassifier from sklearn.tree.

- Initialized the Decision Tree Classifier and set hyperparameters such as criterion='gini' or criterion='entropy' to measure split quality.

- Trained the model on the training dataset using .fit(X_train, y_train).

- Made predictions on the test dataset using .predict(X_test).

### 3. Model Visualization

- Used plot_tree() and export_text() from Scikit-learn to graphically represent the Decision Tree structure.

- Displayed decision rules to understand how features contributed to classification.

### 4. Model Evaluation

- To assess the model’s performance, we used the following metrics:

- Accuracy Score: Measured the percentage of correct predictions.

- Confusion Matrix: Visualized the number of correct and incorrect classifications.

- Precision & Recall: Evaluated the model’s ability to classify positive and negative cases correctly.

- F1-score: Balanced measure of precision and recall.

## Results and Analysis

- The Decision Tree model successfully classified/predicted outcomes with an acceptable accuracy.

- The visualized tree structure provided insights into feature importance and decision-making.

- Performance metrics such as accuracy, precision, and recall confirmed the model’s reliability.

- The confusion matrix helped identify areas where the model performed well and areas needing improvement.

- Hyperparameter tuning, such as adjusting max_depth, improved performance by preventing overfitting.

## Challenges and Learnings

### Challenges Faced:

- Handling imbalanced datasets, which sometimes led to biased predictions.

- Avoiding overfitting, especially when the tree depth was too large.

- Selecting the best hyperparameters for improved performance.

## Key Learnings:

- Feature selection is crucial for improving decision tree accuracy.

- Overfitting can be controlled using pruning techniques or limiting tree depth.

- Decision Trees are interpretable, making them useful for understanding model decisions.

## Conclusion

In this task, we successfully implemented and visualized a Decision Tree model using Scikit-learn. The model effectively classified/predicted outcomes and provided an interpretable representation of decision-making. The results and visualizations demonstrated the importance of feature selection, pruning, and evaluation metrics in developing a robust Decision Tree model.

## Deliverable

### A Jupyter Notebook containing:

- Data preprocessing steps

- Decision Tree implementation code

- Model training and evaluation

- Decision Tree visualization

- Performance analysis and conclusions

## Output

![Image](https://github.com/user-attachments/assets/cfd46240-7411-466c-af1c-49efdb563d06)
![Image](https://github.com/user-attachments/assets/04a436ef-5b9b-47c2-90c9-5cb74f994759)
![Image](https://github.com/user-attachments/assets/8d06de03-4a4b-4401-9420-a68f511134aa)
![Image](https://github.com/user-attachments/assets/4e324d06-5cf2-4d2b-82dd-590044c91e3c)
![Image](https://github.com/user-attachments/assets/1385f8c6-60d6-4ab2-871a-c6fff44057b3)
![Image](https://github.com/user-attachments/assets/d51fc921-bf57-45c4-aaec-89ce1a73df43)
![Image](https://github.com/user-attachments/assets/8ea59b43-8b48-4e7e-9ad8-adf05061a01e)


