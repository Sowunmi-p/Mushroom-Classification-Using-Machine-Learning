# Mushroom Classification Using Machine Learning
Project Overview
This project explores the use of various machine learning models to classify mushrooms as either edible or poisonous based on their physical characteristics. The models used include Logistic Regression, Random Forest Classifier, and Decision Tree models with different criteria (Gini impurity and Entropy). The project aims to assess the effectiveness of these models in accurately predicting the edibility of mushrooms while highlighting potential challenges and areas for future research.

Table of Contents
Project Overview
Data
Models Used
Evaluation Metrics
Results
Conclusion
Critical Evaluation
Future Work
How to Run the Project
Acknowledgments
Data
The dataset used in this project consists of physical attributes of various mushrooms. Each mushroom is labeled as either edible or poisonous. The features include cap shape, cap color, gill size, and many more that provide the necessary inputs for the classification models.

Models Used
Logistic Regression: A simple yet effective linear model that estimates the probability of a mushroom being edible based on its features.
Random Forest Classifier: An ensemble learning method that builds multiple decision trees and merges them to get a more accurate and stable prediction.
Decision Tree Classifier (Gini Impurity): A decision tree model that splits the nodes based on the Gini impurity measure.
Decision Tree Classifier (Entropy): A decision tree model that splits the nodes based on information gain, measured by entropy.
Evaluation Metrics
The models were evaluated using the following metrics:

Accuracy: The percentage of correctly classified instances.
AUC Score: The area under the ROC curve, indicating the ability of the model to distinguish between classes.
Precision, Recall, F1-Score: Metrics that assess the balance between the positive class predictions and their accuracy.
Training Set Score: The accuracy of the model on the training data.
Results
The results from the models were as follows:

Features	Logistic Regression	Random Forest Classifier	Decision Tree (Gini Impurity)	Decision Tree (Entropy)
Accuracy	93.7%	90.7%	94.8%	94.0%
AUC Score	93.67%	90.48%	94.87%	94.1%
Precision (Edible Class)	93%	86%	97%	98%
Precision (Poisonous Class)	95%	96%	92%	91%
Recall (Edible Class)	95%	96%	93%	90%
Recall (Poisonous Class)	92%	84%	97%	98%
F1-Score	94%	91%	95%	94%
Training Set Score	94%	89%	95%	94%
Conclusion
The study successfully demonstrated the use of machine learning models for the classification of mushrooms as either edible or poisonous. Logistic Regression and Decision Tree models provided the highest accuracy, with Decision Tree models using Gini impurity showing the best overall performance in terms of AUC score and balanced precision-recall metrics. However, challenges such as feature selection, class imbalance, and model interpretability were highlighted, suggesting areas for further research.

Critical Evaluation
All models effectively classified mushrooms, with Logistic Regression and Decision Tree models outperforming Random Forest Classifier by a small margin. Decision Tree models displayed robust generalization capabilities with minimal overfitting. AUC scores indicated strong performance in distinguishing between edible and poisonous classes, particularly for the Decision Tree model using Gini impurity.

Future Work
Future efforts should focus on:

Improving model robustness and generalization.
Addressing potential class imbalance issues.
Enhancing data quality and feature selection.
Ensuring the ethical application of machine learning in mushroom classification.
How to Run the Project
Clone the repository to your local machine.
Install the required Python libraries (pandas, scikit-learn, matplotlib, etc.).
Run the Jupyter notebook or Python scripts to train the models and generate predictions.
Evaluate the models using the provided metrics and compare the results.
Acknowledgments
This project was conducted as part of my academic coursework in Data Science. Special thanks to my instructors and peers for their support and feedback throughout the project.
