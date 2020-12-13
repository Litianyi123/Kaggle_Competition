# Kaggle_Competition
This is an exercise of text classification, through the platform of an online data science competition:
https://www.kaggle.com/c/umd-inst414-20f-imdb.

This is a text classification task. Every document (a line in the data file) is a movie review from IMDB. Your goal
is to classify each document into ONE of the two categories, based on whether it needs simplification: 1 if the review
is positive; 0 if the review is negative.

The training data contains 10,000 reviews, already labeled with one of the above categories. The test data contains
5,000 reviews that are unlabeled. The submission should be a .csv (comma separated free text) file with a header
line ”Id,Category” followed by exactly 5,000 lines. In each line, there should be exactly two integers, separated by
a comma. The first integer is the line ID of a test question (0 - 5,000), and the second integer is the category your
classifier predicts one of (0,1).
