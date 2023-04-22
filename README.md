# SC1015 Data Science Mini Project - Fake News 
## About
In the age of digitalisation, the rise of fake news has been at an unprecendented rate, inflicting harm on the society. 
Our mini project aims to apply what we have learnt in the course to come up with a model to classify if a news article is fake or real.

## Repository Contents


## Order of SC1015_Project.ipynb
Our Jupyter notebook has been organised in the following manner:
1. Introduction & Problem statement
2. Data Preparation & Cleaning
3. Data Exploration
4. Machine Learning (Models)

## Problem Statement
How might we determine if news on online platform is real or fake?
Which model would be the most suitable in helping us classify if a news article is real or fake?

## Models Explored
1. Logistic Regression Model
2. Naive-Bayes Prediction Model
3. Decision Tree Classifier Model
4. Passive-Aggressive Classifier Model
5. Support Vector Machine Classifier Model
6. Ensemble

## Conclusion
- Number of words in title does not have a correlation with whether the news article is real or fake.
- Number of retweets is not a good predictor of the whether the news article is real or fake.
- Ensemble model has the highest prediction accuracy of 85.2% out of all models tested.
- Despite the high accuracy of our model, it would be best coupled with human vetting.
- As for future recommendations, we can include datasets that are not politically motivated, use other variables (e.g. pictures, no. of words in articles) as predictors and explore other ensemble models, such as stacking, to better improve the accuracy in predicting fake news.

## Takeaways From This Project
- Lemmatization & Tokenization
- Converting numerical variabile (1/0) into boolean variable
- Creating new variables from existing variables
- New models explored 
- Collaborating using Google Colab

## References
https://www.kaggle.com/datasets/algord/fake-news
https://www.geeksforgeeks.org/ensemble-methods-in-python/
https://machinelearningmastery.com/stacking-ensemble-machine-learning-with-python/
https://www.geeksforgeeks.org/introduction-to-nltk-tokenization-stemming-lemmatization-pos-tagging/
https://www.geeksforgeeks.org/ml-logistic-regression-using-python/
https://www.geeksforgeeks.org/naive-bayes-classifiers/

## Team Members
Shen Jia Cheng - Data extraction & preparation  
Pang Boslyn - Data visualisation & analysis
Tan Yue Hui - Machine Learning
