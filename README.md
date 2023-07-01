# CORONAVIRUS TWEET SENTIMENT ANALYSIS

![image](https://github.com/KapilNarayanSingh/Coronavirus-Tweet-Sentiment-Analysis/assets/117643744/95d1fb48-f27c-4d75-af16-def90237dea0)


### 📋 PROBLEM STATEMENT:

This challenge asks you to build a classification model to predict the sentiment of COVID-19 tweets. The tweets have been pulled from Twitter and manual tagging has been done then.

###  🎯 OBJECTIVE: 

The CoVid-19 pandemic has shaken the very foundation of society wherein people were forced to live inside their houses because of the lockdown being imposed and also the livelihood of almost every section of the society was impacted. 

The objective of our analysis revolved around knowing the sentiments of people from their tweets on Twitter as Twitter is one of the prime means of expression over social media.

###  APPROACH:
-	Text Preprocessing
-	Exploratory Data Analysis 
-	Model Preprocessing
-	Model Training
-	
### 

### 📘 ALGORITHMS USED:
- Logistic Regression with Grid Search CV
- Decision Tree Classifier
- XG Boost 
- KNN
- SVM Classifier for both Count Vector and TF ID Vectorization techniques.
- Naive Bayes
- Random Forest

### PROBLEM FACED:

-	Text preprocessing.
-	Vectorization.
-	Model Training and performance improvement

### CONCLUSION:
- We first evaluated the model on the basis of multiple classification where we have taken multiple sentiments into consideration which includes positive ,negative, neutral, extremely positive and extremely negative sentiment.

- After applying various classification algorithm we come to a conclusion that the best is logistic classification with a score of 61 percent.
- After multiple classification we divided our data into binary classification, in which extremely positive, positive and netral are taken as 0 and extremely negative and negative are taken as 1 for classification.
- The output after Deploying various Model into the system the best algorithm comes out to be Stochastic Gradient Descent.
- We have seen confusion matrix for individual cases prediction and seen that lighter part that is i
has less frequency and darker part has high frequency.


### 📚 References
Random Forest Regressor - https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html 

Gradient Boosting Documentation - https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html


