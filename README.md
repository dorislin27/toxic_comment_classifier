# Toxic Comment Classifier

## Objectives:
Toxic comment classifier is a natural language processing application that allows online platforms to detect the toxicity of a message based on its textual context, with the long term goal to improve  the quality of online conversation. The project answers below questions:
* What’s the probability of each type of toxicity (toxic, severe toxic, obscene, threat, insult, identity hate) for each comment?
* Which words/phrases frequently seen in toxic messages are key to the future prediction?
* When do models make mistakes? If taking the cost of misclassification into account, what are tolerable mistakes and how should models adapt to it? 


## Data Source:
The training data covers 160K comments from English Wikipedia talk page edits, dating from 2004 to 2015. Each comment is manually labeled with one or more toxic types, including toxic, severe toxic, obscene, threat, insult, identity hate.


## Project Structure

###### Text Preprocessing
###### Feature Vector Extraction:
* Bag-of-Words representation
* N-grams
* Tf-idf vectorization

###### Machine Learning Solutions(Multi-label classification):
* logistic regression
* naive bayes
* SVM 
* decision tree
* ensemble model: random forest

###### Key Evaluation Metrics:
ROC and AUC

###### *Other Possible Solutions:
* Use other dataset about hate speech to build a model. And leverage the model to improve the performance of classification model.
* Deep Learning
