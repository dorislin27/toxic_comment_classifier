# Toxic Comment Classifier

## Motivation
Specialized in children’s literature, I’ve always been curious how words influence children’s perception of the world. In the digital era, children get access not only to literature work but also to online comments and articles, which can contain toxic conversations. They might suffer from cyber-bullying and consequent negative influence. The large volume of online comments makes it hard for humans to thoroughly monitor and guard children’s well beings. Natural language processing can effectively tackle the problems by recognizing and reporting the harmful contents.

## Objectives
With the goal to reduce cyber-bullying due to hate speech, the project aims to apply machine learning and natural language processing to predict whether a comment contains hate message and what types of attack it should be assigned to. 

## Dataset Description
The dataset covers 160K comments from English Wikipedia Talk Pages, dating from 2004 to 2015. Each comment is manually labeled with one or more toxic types, including toxic, severe toxic, obscene, threat, insult, identity hate. 

## Project Structure

###### Text Preprocessing
###### Feature Vector Extraction (not consider the semantic relationship):
* Bag-of-Words representation
* N-grams
* Tf-idf model

###### Machine Learning Solutions(Multi-label classification models):
* logistic regression
* naive bayes
* SVM 
* decision tree
* ensemble model: random forest

###### Evaluation:
ROC and AUC

###### *Other Possible Solutions:
* Use other dataset about hate speech to build a model. And leverage the model to improve the performance of classification model.
* Deep Learning
