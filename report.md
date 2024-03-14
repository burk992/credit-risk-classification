# Module 20 Report Template

## Overview of the Analysis

The aim of this study is to assess the effectiveness of two logistic regression machine learning models in forecasting credit risk for loans. We analyzed financial data including loan sizes, interest rates, borrower income, debt-to-income ratios, number of accounts, derogatory marks, and total debt. Our goal was to predict the loan status, categorizing it as either a healthy loan ('0') or a high-risk loan ('1').

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Model 1 Accuracy: The accuracy of Model 1 was 99%. 
	* Model 1 Precision: For healthy loans, the model had a precision of 1.00, which indicates that identified true positive healthy loans with no false positives. For high-risk loans, the precision was .85, meaning that it was effective at identify high-risk loans, however, there were false positives. This is probably okay from an institution standpoint as a manual review of the loan information could indicate if it is a false positive, and this would be unlikely to happen often.
	* Model 1 Recall: For healthy loans, the model had a recall of .99, which means that it almost perfectly identified healthy loans without any instances of false negatives. For high-risk loans, the model had a recall of .91, indicating a high rating of identifing problematic loans with few false positives. Again, this is okay if paired with a requested manual review process.

## Summary

I suggest the use of this model for credit risk management, primarily due to its exceptional precision and recall scores. These high scores signify the model's ability to accurately identify both high-risk loans and healthy ones, minimizing the likelihood of erroneously categorizing loans and reducing the financial risks associated with lending. With its robust performance in precision, the model ensures that loans identified as high-risk are indeed so, minimizing false alarms and the potential for approving risky loans. Simultaneously, its high recall score demonstrates its effectiveness in capturing the majority of actual high-risk loans, thereby minimizing the chance of missing critical instances that could pose significant financial risks. By leveraging a logistic regression model with such outstanding precision and recall scores, financial institutions can significantly enhance their risk management practices, ensuring more informed and prudent lending decisions while safeguarding their financial stability.