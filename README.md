# Classification 
Download the data  le \auto-mpg.data" from UCI ML Repository.
There are 398 rows (i.e., 398 different kinds of cars), and 9 columns (the car attributes and
name). Before we do any analysis, we need to clean the raw data. In particular, some values
are missing for this dataset.  For simplicity, we remove those rows with missing
values. Also we remove the last column of car names, which is text/string. These two deletions lead to a new cleaned data set of 392 observations
and 8 columns. 

(b) Create a binary variable, mpg01, that contains a 1 if mpg contains a value above its median,
and a 0 if mpg contains a value below its median. This binary variable will be the response variable. 

(c) Explore the data graphically in order to investigate the association between mpg01 and the
other features. Which of the other features seem most likely to be useful in predicting mpg01

(d) Split the data into a training set and a test set.

(e) perform the following classi cation methods on the
training data in order to predict mpg01 using the variables that seemed most associated with mpg01


(1) LDA (2) QDA (3) Naive Bayes (4) Logistic Regression

(5) KNN with several values of K


