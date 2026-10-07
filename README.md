# ML-Activity

## 1. Project Title

Ensemble Learning Using Pima Indians Diabetes Dataset

## 2. Objective

The objective of this practical is to implement ensemble learning techniques
for diabetes prediction using the Pima Indians Diabetes Dataset.

The following ensemble techniques are implemented:

- Bagging
- Boosting
- Voting
- Stacking

## 3. Dataset

The dataset used for this practical is the Pima Indians Diabetes Dataset.

The dataset contains information about patients and is used to predict
whether a person has diabetes.

### Dataset Features

1. Pregnancies
2. Glucose
3. BloodPressure
4. SkinThickness
5. Insulin
6. BMI
7. DiabetesPedigreeFunction
8. Age

### Target Variable

Outcome

- 0 = No Diabetes
- 1 = Diabetes

## 4. Machine Learning Models

Three base models are used:

### 1. Decision Tree

Decision Tree is a supervised machine learning algorithm that makes
predictions using a tree-like structure of decisions.

### 2. Random Forest

Random Forest combines multiple decision trees and produces a prediction
based on the results of those trees.

### 3. AdaBoost

AdaBoost is a boosting algorithm that combines multiple weak learners
to create a stronger classifier.

## 5. Ensemble Techniques

### Bagging

Bagging trains multiple models on different samples of the training data
and combines their predictions.

### Boosting

Boosting trains models sequentially and gives more importance to examples
that were incorrectly classified by previous models.

### Voting

Voting combines predictions from multiple machine learning models and
selects the final prediction based on the votes.

### Stacking

Stacking combines multiple base models and uses another model called a
meta-model to make the final prediction.

## 6. Libraries Used

The following Python libraries are used:

- Pandas
- Scikit-learn

## 7. Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## 8. Files in This Repository

| File | Description |
|---|---|
| `Ensemble Learning.ipynb` | Complete Python program |
| `diabetes.csv` | Pima Indians Diabetes Dataset |
| `README.md` | Project description and information |

## 9. Expected Result

The program compares the performance of different machine learning
models and ensemble learning techniques using the Pima Indians Diabetes
Dataset.

The performance is measured using accuracy, precision, recall, F1 score,
and confusion matrix.

## 10. Conclusion

Ensemble learning combines the predictions of multiple machine learning
models to improve classification performance. In this practical,
Bagging, Boosting, Voting, and Stacking techniques are implemented for
diabetes prediction using the Pima Indians Diabetes Dataset.
