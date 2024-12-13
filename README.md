# Animal Classification using Machine Learning Models

## Overview
This project explores and evaluates the performance of various machine learning models, including Random Forest, Gradient Boosting, Support Vector Machine, and Logistic Regression, for classifying animals based on their characteristics. The focus is on understanding the strengths and limitations of each model and selecting the best-performing algorithm.

## Dataset
The dataset contains features describing animals, such as:
- `hair`
- `feathers`
- `eggs`
- `milk`
- And other binary attributes indicating animal traits.

The target variable, `type`, represents the classification category for each animal.

## Models Used
1. **Random Forest Classifier**
   - Ensemble learning technique using multiple decision trees.
2. **Gradient Boosting Classifier**
   - Sequential tree-building algorithm focusing on correcting errors.
3. **Support Vector Machine (SVM)**
   - Supervised learning algorithm for classification with a hyperplane.
4. **Logistic Regression**
   - Linear model predicting the probability of class membership.

## Key Features
- Data preprocessing, including encoding, cleaning, and train-test splitting.
- Feature importance analysis for interpretability.
- Comprehensive evaluation using accuracy, precision, recall, and confusion matrices.

## Results
| Model                  | Accuracy |
| ---------------------- | -------- |
| Random Forest          | 95.24%   |
| Gradient Boosting      | 100%     |
| Support Vector Machine | 95.24%   |
| Logistic Regression    | 95.24%   |

Gradient Boosting achieved the highest accuracy and perfect classification for all classes.


## Install dependencies:

- Python 3.8+
- Scikit-learn
- pandas
- matplotlib
- Seaborn