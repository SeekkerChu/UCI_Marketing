# UCI_Marketing
End-to-End Data Science Project

1. Project Overview
This project predicts whether a client will subscribe to a term deposit using the UCI Bank Marketing dataset. Used by Unsupervised Learning (K-means Clustering) to discover natural segments within the customer base and Supervised Learning (Logistic Regression) for classification. The model's decisions are interpreted using SHAP to identify key economic and seasonal drivers.

2. Dependencies
To run this project (in Google Colab or a local Python environment), you need the following libraries installed:

(pandas, numpy, matplotlib, seaborn, missingno, scikit-learn, shap, logging, os)


3. Run Instructions
	1. Environment Setup: Open the notebook in Google Colab.
	2. Import Libraries
	3. Data Loading: Ensure the dataset is uploaded to the Colab environment or specify the correct file path.
	4. Workflow Execution: Pre-processing, Classification, Optimization, Clustering
	5. Visualization: ROC, SHAP and PCA/t-SNE


4. Dataset Justification
The UCI Bank Marketing dataset was selected for the following reasons:

Feature Richness: It is allowing for multi-dimensional analysis.

Real-World Optimization: As a classic imbalanced classification problem, it is ideal for demonstrating how threshold tuning by F1-score balances the imbalance target value "y".

Interpretability: The inclusion of time-based variables (like month_mar) and economic metrics makes it an excellent candidate for SHAP, revealing exactly why certain clients are more likely to subscribe.
