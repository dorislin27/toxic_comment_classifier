# toxic_comment_classifier
Toxic Comment Classifier

## Objectives
With the goal to reduce cyber-bullying due to hate speech, the project aims to apply machine learning and natural language processing to predict whether a comment contains hate message and what types of attack it should be assigned to. 

## Dataset Description
The dataset covers 160K comments from English Wikipedia Talk Pages, dating from 2004 to 2015. Each comment is manually labeled with one or more toxic types, including toxic, severe toxic, obscene, threat, insult, identity hate. 

## Project Structure

###Text Preprocessing
###Feature Vector Extraction (not consider the semantic relationship)
1.bag-of-words representation
2.N-grams
3.Tf-idf model

###Machine Learning Solutions(Multi-label classification models)
1.logistic regression
2.naive bayes
3.SVM 
4.decision tree
5.ensemble model: random forest

###Evaluation
ROC and AUC

### Other Possible Solutions:
Use other dataset about hate speech to build a model. And leverage the model to improve the performance of classification model.
Deep Learning
