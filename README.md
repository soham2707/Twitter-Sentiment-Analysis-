# Twitter-Sentiment-Analysis-
This a project of twitter sentiment analysis using machine learning(Support Vector Machines,Naive Bayes), deep learning(LSTM), Transformer(BERT,ROBERTA).

We know that Twitter is a social media platform. Here everyone can create an account and portrayed their own views. Apparently, we can see that the power of portraying independent views in social media is immeasurable but there are some bad sides too. In some cases, people are conveying their opinion with less research and not knowing the fact on social media. As a consequence people are getting confused about the fact, which information is real and which information is fake.


Goal:
-----

Our goal is to check the sentiment of a tweet over a topic. It can massively be used to check the sentiment of a new product. There are 3 results over the sentiment analysis. The sentiment can be positive, negative, neutral. Based on that result we can analyse the transparency of the new product.


DATASET:
----
The dataset is based on the tweet of Indian Prime Minister Narendra Modi. By using this dataset we will identify the sentiment of common people. Here the number of the tweet is 1,62,981.

"Twitter US Airline Sentiment" Analyze how travelers in February 2015 expressed their feelings on Twitter. Here the number of the tweet is 14,000.

Approach:
----
**_Here there are 3 type of approach._**

├──  **Machine Learning** |-- **SVM , Naive Bayes**

├── **Deep Learning** |-- **LSTM**

├── **Transformer** |-- **BERT, ROBERTA**


Basic Description on Approach:
----

## Machine Learning:

**_SVM_**:

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

The goal of the SVM algorithm is to create the best line or decision boundary that can segregate n-dimensional space into classes so that we can easily put the new data point in the correct category in the future. This best decision boundary is called a hyperplane.

SVM chooses the extreme points/vectors that help in creating the hyperplane. These extreme cases are called as support vectors, and hence algorithm is termed as Support Vector Machine. Consider the below diagram in which there are two different categories that are classified using a decision boundary or hyperplane:

<p align="left">
    <img src="https://static.javatpoint.com/tutorial/machine-learning/images/support-vector-machine-algorithm.png" width="670" height="470">
  </p>



**_Naive Bayes_**:

Naive Bayes classifier is a probabilistic machine learning model that’s used for classification task. The crux of the classifier is based on the Bayes theorem.

Bayes Theorem:

![UI](1.jpg)

Using Bayes theorem, we can find the probability of A happening, given that B has occurred. Here, B is the evidence and A is the hypothesis. The assumption made here is that the predictors/features are independent. That is presence of one particular feature does not affect the other. Hence it is called naive.



























Check out my Medium article ,where I have explained in detail.

https://nandisoham2017.medium.com/twitter-sentiment-analysis-using-machine-learning-approaches-14fba1b8e357
