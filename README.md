# Machine Learning: Digit Recognizer


**Data Source**: The data set comes from the **Kaggle Digit Recognizer competition**. 

**Machine Learning Algorithms**: Decision Tree and Naive Bayes 

**Goal**: The goal is to recognize digits 0 to 9 in handwritten images. Because the original data set is too large, I have systematically sampled 5% of each of the original training and testing data, stored in files called digit-train.csv and digit-test.csv, respectively.
You are going to use the training data to construct prediction models using both Naïve Bayes and decision tree algorithms. Tune their parameters to get the best model (measured by cross-validation) and compare which algorithms provide better performance on the testing data.

**Algorithm Performance Comparison**

After performing both machine learning algorithms on the data set, even though we get high accuracy on the decision tree algorithm, the model overfits when we observe the model accuracy on train and test data, i.e.,**89.3% on train and 76.8% on test data**. In the case of the Bernoulli Naïve byes algorithm, we get an accuracy of **84.09% on train data and 82.23% on test data**. I printed the classification report for both models to observe the precision value.

<img width="885" alt="Screenshot 2023-11-09 at 8 19 12 AM" src="https://github.com/jasumonga17/Digit-Recognizer-ML-NaiveBayes/assets/76562774/8008c5da-f934-4c45-b02a-ae7a1ca90e77">

**Precision and Recall** for Naive Bayes Model

<img width="374" alt="Screenshot 2023-11-09 at 8 20 09 AM" src="https://github.com/jasumonga17/Digit-Recognizer-ML-NaiveBayes/assets/76562774/4339bfd1-63d4-4521-8c39-e61404f8a4f6">

In the above table, Precision specifies the number of times the predicted value is the same as the actual value. For digit 7, we have the highest precision of 93%. Recall specifies out of all the actual results, how many were actually right? Precision is the lowest for digit 9, i.e., 67%.





