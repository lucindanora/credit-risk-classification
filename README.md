# credit-risk-classification

Instructions:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report.


Answer the following question:
    How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

References/Resources: Completed with study group, and class activites, chatgpt

# Module 12 Report 
## Analysis

The primary objective of this credit risk analysis is to anticipate loan risk by leveraging historical lending data sourced from a peer-to-peer lending company. This involves partitioning the data into training and testing sets and subsequently constructing a logistic regression model using the original dataset.

The financial data under consideration includes comprehensive information on loans, categorizing them as either healthy (0) or unhealthy/high risk (1). Employing Machine Learning techniques, our goal is to discern and classify loans into these categories based on the status provided by the lending company.

Utilizing the furnished dataset, we meticulously developed a logistic regression model to achieve this classification.


## Results

* Machine Learning Model 1: Logistic Regression
  * Accuracy 0.99
   * The logistic regression model achieved an impressive accuracy score of 0.99, indicating a 99% correct prediction rate and overall accuracy in loan outcome predictions.
  
  * Precision:
   * Healthy Loans:1.0
    * The precision for healthy loans is 1.00, implying that all loans predicted as healthy and low risk were indeed low risk.
   * High Risk Loans: 0.87
    * For high-risk loans, the precision is 0.87, indicating that 87% of predicted high-risk loans were accurately classified as such.

  * Recall Score:
    * Healthy Loans:1.00
     * The recall score for healthy loans is 1.00, meaning the model correctly identifies all healthy loans.
    * High Risk Loans: 0.95 
     * The recall score for high-risk loans is 0.95, demonstrating that the model effectively identifies 95% of high-risk     loans, resulting in a low false negative rate and suggesting a high capacity for capturing high-risk loans effectively.


## Summary


The logistic regression model, Machine Learning Model 1, exhibits robust performance in predicting loan outcomes. With an accuracy score of 0.99, it correctly predicts loan results for 99% of cases. Precision analysis reveals a perfect identification of healthy loans (1.00) and a slightly less perfect 87% precision for high-risk loans. Furthermore, the recall scores showcase a perfect identification of healthy loans (1.00) and an excellent 95% recall for high-risk loans, indicating the model's efficacy in capturing a significant proportion of high-risk cases with a low false negative rate. Overall, Machine Learning Model 1 demonstrates high accuracy and reliability in predicting loan risks. 

I would however want their to be a human componant to this analysis, as there are always extenuating circumstances that should be considered. 
