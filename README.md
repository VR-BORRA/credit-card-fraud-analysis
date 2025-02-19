# Credit Card Fraud Analysis

Project Team: 
Vikram Borra, Larry Pavlik, Austin Cappetta, Justin Sansbury, Gabriel Jean-jumeau

## Summary
Our team, operating under the name FraudBusters, aims to conduct a comprehensive analysis and prediction of various types of fraudulent activities within a large-scale dataset of 10 million bank transaction records. By leveraging advanced data analytics and machine learning techniques, we seek to identify patterns and trends that characterize different fraud types within the database. Our objective is to categorize these fraud instances, develop predictive models for forecasting future fraudulent behavior, and continuously refine our approach for all four distinct categories of fraud present in the dataset. Through this process, we aim to provide actionable insights and enhance the detection and prevention of fraud in banking systems

# Research Questions
Can we predict the chance of fraud?

What is the most effective way of calculating the
probability of fraud?

## Overview

## Approach 
In our fraud prediction project, we adopted a robust ensemble of machine learning models to deliver accurate and reliable results. We began by utilizing K-Nearest Neighbors (KNN) to classify transactions based on proximity, allowing us to capture patterns in data and identify potential fraud. We also employed a Decision Tree Model, which provides clear decision rules, helping us to interpret and understand the classification process. To further enhance prediction accuracy, we incorporated a Random Forest Classifier, an ensemble learning technique that combines multiple decision trees for a more robust and generalized prediction. Additionally, Logistic Regression was used to model the relationship between features and the likelihood of fraud, providing a probabilistic framework. To ensure optimal model performance, we performed Optimization techniques to fine-tune hyperparameters and achieve the best possible results. This comprehensive approach allowed us to leverage the strengths of each algorithm and deliver a strong, well-rounded fraud detection system.
## Findings

## Hypothesis

## Conclusion

### Accuracy and R2 Comparsion across 4 models
|                | Logistic Regresssion | Random Forest Classifier | Decision Tree      | K Neighbors Classifier (K=5) |
|----------------|----------------------|--------------------------|--------------------|-------------------------------|
| **Accuracy Score** |       0.95858       |         0.99999         |      0.99999      |            0.99882           |
| **Score**          |       0.95858       |         0.99999         |      0.99999      |            0.99882           |
| **R2**             |   0.48440  |    0.99990    | 0.99990 |       0.98536      |

<figure>
  <img src="visuals\dt_cf.jpg" width="500" height="500" alt="Decision Confusion Matrix">
</figure>


References:
