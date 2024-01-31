

CA02 Strategy Solution

Objective: 

The objective is to predict whether an email is (i) spam or (ii) not spam.
Overview: There are several types of ML (e.g., regression, clustering, recommendations).
Natural language processing (NLP) pipelines resemble regular ML pipelines; however, NLP
pipelines are mainly concerned with transforming text into numbers, which isn’t necessarily the
case for many ML pipelines. Our objective is an NLP task, which falls under the classification
type of ML since it focuses on language and text. The classification pre-processes in NLP must
convert the text to zero and one’s as well as a dictionary (or bag-of-words) as a vector or
matrix. Once the pre-processing is complete, the data is split (e.g., 80% for training and 20% for
testing). The training data consists of features (e.g., X_train) and a target (e.g., y_train). A model
is then generated from the trained data (e.g., y_pred), which is compared to the testing dataset
(e.g., y_test). The comparison analysis results in an accuracy score, which can be further
visualized by a confusion matrix.

Our strategic approach is as follows:
1. Acquire the data
2. Pre-process the data
a. Open each file (i.e., email)
b. Tokenization of words (generate bag-of-words)
3. Split the data
a. X_train + y_train (e.g., 80% of the entire dataset)
b. X_test + y_test (e.g., 20% of the entire dataset)
4. Instantiate a classifier
5. Fit the classifier to the training data (i.e., X_train and y_train)
6. Generate predicted tags (i.e., X_test)
7. Calculate an accuracy score (i.e., y_test, y_pred)
a. Visualize the accuracy with a confusion matrix
