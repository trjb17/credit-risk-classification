# credit-risk-classification
Overview of the Analysis
This analysis is to evaluate the performance of a logistic regression used to predict loan statuses, to classify loans as either 0 (healthy loan) or 1 (high-risk loan). This analysis aims to determine how well the model can distinguish between these two classes credit risk classification.

Results
Accuracy Score: 0.99

The model correctly classified 99% of the total instances in the test set.
Precision Score:

Class 0 (Healthy Loan): 1.00
Class 1 (High-Risk Loan): 0.85
Precision measures the accuracy of positive predictions. For Class 0, the precision is 100% perfect healthy loans. For Class 1, the precision is slightly lower of 85%, meaning there were some misclassifications of high-risk loans.

Class 0 (Healthy Loan): 0.99
Class 1 (High-Risk Loan): 0.91
Recall measures the model's ability to identify all relevant instances. The model successfully identified 99% of all actual healthy loans compared to 100% precision and 91% compared to 85% precision of all actual high-risk loans.

Summary
The logistic regression model demonstrates excellent performance in classifying loans:

Overall Accuracy: The model achieves a high accuracy score of 99%, indicating that it correctly classifies most loans in the dataset.

Class-wise Performance:

For Class 0 (healthy loans), the model exhibits perfect precision and very high recall, showing that it is highly effective at predicting healthy loans.
For Class 1 (high-risk loans), the model shows good recall and a respectable precision score. Although there are some misclassifications of high-risk loans as healthy, the model performs well in identifying the majority of high-risk loans.
Macro and Weighted Averages: The model’s macro and weighted average scores further support its effectiveness, with high precision, recall, and F1-scores.

