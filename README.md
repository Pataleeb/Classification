# Classification 
Download the data  le \auto-mpg.data" from UCI ML Repository.
There are 398 rows (i.e., 398 di erent kinds of cars), and 9 columns (the car attributes and
name). Before we do any analysis, we need to clean the raw data. In particular, some values
are missing for this dataset. Many statistical methods have been proposed to deal with missing
values, and please conduct literature research by yourself. For the purpose of simplicity in this
homework, here we adopt a simple though ine cient method to remove those rows with missing
values. Also we remove the last column of car names, which is text/string and may cause trouble
in our numerical analysis. These two deletions lead to a new cleaned data set of 392 observations
and 8 columns. To save your time, you can also directly download the cleaned data from the  le
\Auto.csv" from Canvas.
(b) Create a binary variable, mpg01, that contains a 1 if mpg contains a value above its median,
and a 0 if mpg contains a value below its median. This binary variable will be the response variable
in this homework. Note that you need to  rst compute the median value of the mpg variable in the
data set.
(c) Explore the data graphically in order to investigate the association between mpg01 and the
other features. Which of the other features seem most likely to be useful in predicting mpg01?
(d) Split the data into a training set and a test set.
(e) perform the following classi cation methods on the
training data in order to predict mpg01 using the variables that seemed most associated with mpg01
in (c). What is the test error of the model obtained?
(1) LDA (2) QDA (3) Naive Bayes (4) Logistic Regression
(5) KNN with several values of K: Use only the variables that seemed most associated with
mpg01 in (c). Which value of K seems to perform the best on this data set?
(6) (Optional) PCA-KNN. The Principal Component Analysis (PCA) or other dimension
reduction methods can easily be combined with other data mining methods. Recall that the essence
of the PC-reduction is to replace the p-dimensional explanatory variable xi = (xi1; : : : ; xip); for
i = 1; : : : ; n; with a new p-dimensional explanatory variable ui = (ui1; : : : ; uip); where ui = Ap pxi:
Then we can apply standard data mining methods such as KNN to the  rst r(  p) entries of the
ui's, (ui1; : : : ; uir); to predict Yi's. Find the testing errors when the KNN with di erent values of
K (neighbors) is applied to the PCA-dimension-reduced data for di erent r = p - 1; p - 2; ..... 1
