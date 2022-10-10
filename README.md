# M14_AlgorithmicTrading

# Establish A Baseline Performance
Baseline Predicted Cumulative Returns were slightly less than the actual returns in the baseling trading algorithm.

<img width="385" alt="Screen Shot 2022-10-09 at 7 14 40 PM" src="https://user-images.githubusercontent.com/39920761/194788257-9c025d84-92e2-4acd-8a17-76b047104e44.png"> *Baseline Performance SVM Short: 4 / Long: 100

# Tune the Baseline Trading Algorithm
The Baseline algorithm when tuned with the Support Vector Machine Model with a rolling short average of 3 and a long of 30 was able to create far greater cumulative returns starting mid way through the year 2018 and into the current year data in 2021 in comparison to the baseline model which appeared to trail actual returns.

<img width="385" alt="Screen Shot 2022-10-09 at 7 19 04 PM" src="https://user-images.githubusercontent.com/39920761/194788464-f65f8dad-91f9-42e1-bb66-8cf3fafa19ef.png"> *Tuned Performance SVM Short: 3 / Long: 30

# Evaluate a New Machine Learning Classifier
When evaluating a new Machine Learning Classifier such as Logistic Regression there appeared to be some initial signals of improved strategy returns only to be quickly reversed to drop quickly in comparison to the actual returns.
<img width="386" alt="Screen Shot 2022-10-09 at 7 17 16 PM" src="https://user-images.githubusercontent.com/39920761/194788378-40b31dc6-8998-4e59-83b8-61759d190ece.png"> Baseline Performance Logistic Regression Short: 4 / Long: 100


<img width="393" alt="Screen Shot 2022-10-09 at 7 20 22 PM" src="https://user-images.githubusercontent.com/39920761/194788523-d8d9e6db-6e30-4db6-b02a-250bff25a287.png"> Tuned Performance Logistic Regression Short: 3 / Long: 30


# Evaluation Report Summary
From, my analysis I can provide a recommendation to use the Support Vector Machine model over a logistic regression model. Along with recommending reducing the date range of both the short and long term rolling averages in the SVM Model. It appears eliminating some of the historical weight from the averaging helped to provide greater returns.
