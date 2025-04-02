# ML-Project: Classifying MNIST Datasets

This team project explores various supervised learning techniques on two MNIST datasets. The objective was to compare classification models in terms of predictive performance, tuning, and bias-variance trade-offs. Each team member focused on different models to evaluate performance across datasets, explore hyperparameter optimization, and analyze model behavior.

---

## Models and Methods

The following models were implemented:
- **Logistic Regression**
- **K-Nearest Neighbors**
- **Decision Tree** *(by Ji Hyun Kim)*  
- **Random Forest** *(by Ji Hyun Kim)*  
- **AdaBoost** *(by Ji Hyun Kim)*
- **Support Vector Machine (SVM)**
- **Neural Network**

Key metrics used in cross-validation:
- Accuracy, Precision, Recall, F1 Score, AUC

---

## Key Findings
- **Decision Trees**: Entropy outperformed Gini in both datasets. Careful tuning of max_depth and min_samples_leaf prevented overfitting and improved generalization.
- **Random Forests**: Showed robust performance with relatively shallow trees and ensemble size tuning. Reduced overfitting compared to single-tree models.
- **AdaBoost**: Demonstrated high performance on dataset 1 but tended to overfit on dataset 2 with too many estimators.
- **Neural Networks**: Learning rate and number of hidden units had the most impact on performance; weight and bias initialization had less significant effect.

---

## Project Structure
- /data/ # Raw datasets (dataset1 & dataset2)
- /notebooks/ # Main analysis in final_project.ipynb
- /results/ # Final presentation slides & report
- Readme.md # Project documentation

---

## How to Run
1. Clone this repository: git clone https://github.com/kmjhyn/ML-Project.git
2. Launch the notebook *final_project.ipynb*
3. You may need to update data paths depending on your local setups
4. Install required packages if needed

---

## About the Course
- Course: CS6316 Machine Learning
- Instructor: Prof. Aidong Zhang
- Institution: University of Virginia
- Semester: Fall 2023

---

## Contributions
- Ji Hyun Kim implemented and analyzed Decision Tree, Random Forest, and AdaBoost models, including parameter tuning, cross-validation, and report writing.
- See final_project.ipynb for complete implementation details.

---

## Contact
- Name: Ji Hyun Kim
- Github: [kmjhyn](https://github.com/kmjhyn/)
- Email: [school](mqa4qu@virginia.edu) [personal](jihyunkim1620@gmail.com)
- LinkedIn: [linkedin.com/in/jihyunkim1620](https://www.linkedin.com/in/jihyunkim1620/)
