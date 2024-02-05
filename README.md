# credit-risk-classification
I used lending data to build a machine-learning model to assess borrowers and identify if a loan to them would be considered healthy or high-risk.

In this model, I used the lending_data.csv with information on borrowers and train_test_split on various sample sizes to find an accuracy score on both healthy and high-risk loans to train my model for the best results I could obtain. 

### Machine Learning Model 1:
    - Model 1 Accuracy: 0.952.
    - Model 1 Precision: for healthy loans the precision is 1.00, for high-risk loans the precision is 0.85.
    - Model 1 Recall: for healthy loans the recall score is 0.99, for high-risk loans the recall score is 0.91.

### Machine Learning Model 2:

    - Model 2 Accuracy: 0.995.
    - Model 2 Precision: for healthy loans the precision is 0.99, for high-risk loans the precision is 0.99.
    - Model 2 Recall: for healthy loans the recall score is 0.99, for high-risk loans the recall score is 0.99.

# Summary
    - It appears model 2 with the oversamples data allowed the machine-learning model to have a better accuracy with making predictions. 
    - Since in general high-risk loans are the ones to have a more accurate prediction, I believe that losing the .01 on healthy loans is better for the great increase in precision on the high-risk loans. 