# Berkeley AI/ML Certificate — Module 17

This module focuses on analyzing a real-world marketing dataset from a Portuguese banking institution. The objective is to explore the data, understand the factors that influence client responses to marketing campaigns, and evaluate several machine‑learning models to determine which approach yields the best predictive performance. Based on the analysis, recommendations for next steps and future improvements are provided.

## 📊 Data Source
The dataset is publicly available through the UCI Machine Learning Repository:
https://archive.ics.uci.edu/dataset/222/bank+marketing
It contains information from direct marketing campaigns conducted by a Portuguese bank, including client demographics, contact history, and campaign outcomes.

## 🔍 Key Findings
✔️ Best-Performing Model: Decision Tree
Among all the models evaluated, the Decision Tree classifier emerged as the top performer.
Its advantages include:

High interpretability: The tree structure makes it easy to visualize how predictions are made.
Clear feature usage: You can directly see which attributes the model prioritizes during classification.
Transparent decision paths: Each branch of the tree represents a logical sequence that leads to the final prediction.

## 🌱 Important Predictive Features
Based on the Decision Tree visualization and feature splits, the following attributes were most influential in predicting whether a client would subscribe to the bank’s term deposit offer:

Social and economic indicators (e.g., employment variation rate, consumer confidence index)
Number of contacts made during the campaign
Days since last contact with the client
Type of communication channel (telephone, cellular)
Marital status

These features consistently appeared in early and influential splits of the tree, indicating strong predictive power.

## 🧪 Comparison of Other Models
Additional models evaluated include:

Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Classifier (SVC)
Stochastic Gradient Descent (SGD)

## Summary of Comparisons

Performance: These models produced similar accuracy scores overall.
Training Time:

Fastest: Logistic Regression and KNN
Slower: SVC and SGD, due to more complex optimization steps

## Interpretability:

It is relatively difficult to extract feature importance from SVC and SGD models compared to tree‑based methods.
Logistic Regression provides coefficients, but they are harder to interpret on raw categorical encodings.

Overall, while these models perform respectably, Decision Trees offer the strongest combination of accuracy + interpretability for this dataset.

## 📓 Notebook Reference
The full analysis, code, and visualization
https://github.com/asadbajwa123/B_Module_17/tree/main

