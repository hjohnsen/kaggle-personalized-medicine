# kaggle-personalized-medicine
Code for a Kaggle competition-- [Personalized Medicine: Redefining Cancer Treatment](https://www.kaggle.com/c/msk-redefining-cancer-treatment)

This repository contains three files, the "playground" script that was used to iterate through models and features,  the submission script which uses the features and model that were ultimately used for submission, and a debrief document I wrote after the competition to keep track of what I tried on during the process. 

The competition was to build a model capable of using scientific paper text to generate predictions for what class a particular cancer mutation might be (for example, gain of function, loss of function, etc.). This annotation is currently done by human expert curators and is very time consuming. For this task, I tried using a number of NLP features including words present in the article and/or abstract, words present near mentions of the gene and/or mutation, bigrams as well as biological features, such as molecular lesion. I tested several models, including a random forest, Naive Bayes, XGBoost, and logistic regression. I participated in this challenge together with my husband. The competition had some unfortunate extenuating circumstances that resulted in it becoming a two-stage competition with private test data that were not well-matched to the training data. My model ranked 136th out of 1386 on the first-stage public leaderboard and ranked 175th out of 357 on the second-stage private leaderboard.
