# Genre Classification of Song Lyrics 

## Comparison of Logistic Regression, Random Forest, Adaboost, and Naive Bayes Classifiers

### Jeremy Cui and Jason Stitt
### Northeastern University - Khoury College of Computer Science
### April 18, 2022

This project attempts to predict a song’s genre based on its lyrics. A project such as this one could aid many parties in the music industry. A model that correctly predicts song genre based on lyrics would enable artists to create music and publish it without having to indicate the genre itself. The model would then determine the genre to avoid mis-classifying a genre and keep music listeners happy. The model could also be enhanced in the future to include sub-genres and produce even better recommendations as a result.
This project compares the performance of various machine learning models on the problem using song lyrics as the input variable and genres as the label. Models whose performance are being observed are the logistic regression model, naive Bayes, Random Forest with bagging, and AdaBoost classifier. Variations of some models are also tested, such as comparing gini impurity to 'entropy loss' for random forest splits.
Featurization of the lyrics is done using the tf-idf, a basic featurization method based on commonality of terms across documents for natural language tasks.

## Notebook
The notebook containing the code can be run from top to bottom. 
