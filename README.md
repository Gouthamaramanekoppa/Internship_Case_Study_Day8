# Internship_Case_Study_Day8

Overview
On Day 8, a feasibility analysis was conducted to evaluate the shortlisted AI models based on practical implementation factors. The goal was to determine which algorithm would be most suitable for the fraud detection system considering performance, complexity, scalability, and implementation effort.

A structured decision matrix was created to compare the models objectively.

Evaluation Criteria
The following criteria were selected for evaluating the AI models:

1. Prediction Accuracy
   Ability to correctly detect fraud transactions.

2. Handling Imbalanced Data
   Capability to work effectively when fraud cases are very rare.

3. Computational Efficiency
   Training time and prediction speed.

4. Scalability
   Ability to handle large transaction datasets.

5. Model Interpretability
   Ease of understanding model decisions.

6. Implementation Complexity
   Difficulty of building and deploying the model.


Decision Matrix
| Model | Accuracy Potential | Imbalanced Data Handling | Computational Cost | Interpretability | Implementation Complexity | Overall Score |
|------|-------------------|--------------------------|--------------------|------------------|--------------------------|---------------|
| Logistic Regression | Medium | Medium | Low | High | Low | 7/10 |
| Random Forest | High | High | Medium | Medium | Medium | 8.5/10 |
| XGBoost | Very High | High | Medium | Medium | High | 9/10 |
| Neural Network | High | Medium | High | Low | High | 7.5/10 |


Feasibility Discussion

Logistic Regression
Suitable as a baseline model due to its simplicity and interpretability. However, it may not capture complex fraud patterns effectively.

Random Forest
Provides strong performance and robustness. It handles nonlinear relationships well and is widely used in fraud detection systems.

XGBoost
Offers the highest predictive performance and handles imbalanced datasets efficiently. It is commonly used in real-world fraud detection systems and machine learning competitions.

Neural Networks
Capable of learning complex patterns but requires larger datasets and longer training time. It is less interpretable compared to tree-based models.


Selected Models for Implementation
Based on the feasibility analysis, the following models were selected for prototype implementation:

1.Random Forest
2.XGBoost

These models provide the best balance between accuracy, scalability, and practical deployment.

Logistic Regression will be used as a **baseline model for comparison**.

