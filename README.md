# Spam_email_detect

This is a spam email detection model using machine algorithm -> Naive Bayes(MultinomialNB).
Multinomial Naive Bayes (MNB) is a very popular and efficient machine learning algorithm that is based on Bayes’ theorem. It is commonly used for text classification tasks where we need to deal with discrete data like word counts in documents. We have also used other alogorithms like SVM and Random forrest to compare which model suits the best.

Here, we have used the basic approach to vectorize the text documents manually and then detect accordingly. Then a better approach using pipeline(sklearn.pipeline) has been used so that all the steps are encapsulated into a single object and the emails can be directly detected.
Also, the model performance is checked by confusion matrix imported from sklearn.metrics.
