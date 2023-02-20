# Spam_Ham_Classifier_ML

Email/text messages have become a crucial part of our daily life as it is handy and easy to use. Since the user batch is enormous and contains a lot of sensitive information, it is susceptible to being compromised. Hackers can steal your information, leading to data theft, time wasted, and other security concerns. This brings us to the need to introduce a filter that can segregate emails into spam and ham. 

Ham refers to genuine mail that is important to the user and is informative for his means. In contrast, Spam is spurious mail sent from unreliable sources with harmful intentions. In this blog, we will be studying how to segregate such messages into spam/ham using differnt ML models training and testing. 


#### The Best Model among these is Multinomial Naive Bayes with the accuracy score of: 98%

### Naive Bayes Classifiers
Naive Bayes classifiers are one of the most used predictive algorithms in machine learning which is used to predict the probability of the occurrence of the data under observation, assuming that each data point is independent in the given dataset. Using binary or categorical input values, the approach is simplest to grasp. We may calculate the likelihood of X occurring using the Bayes theorem, given that C has occurred. In this case, X represents the evidence, and C represents the hypothesis. The predictors/features are assumed to be independent in this case. That is, the existence of one trait does not affect the present. As a result, it is said to as naïve. 

The Bayes classifiers determine the likelihood of a particular event occurring (in our example, spamming a message) based on the combined probabilistic distributions of several other occurrences (in our case, the appearance of certain words in a message). We'll get into the mechanics of the Bayes Theorem later in the mission, but first, let's get a sense of the data we'll be dealing with.
