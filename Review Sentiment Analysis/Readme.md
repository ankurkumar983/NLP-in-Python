
Calculate the review sentiment score of a review in XML format. Steps used in the process are:
Decode the review using BeautifulSoup
Cleaning the text (Punctuation removal,Remove short worlds 1 charecter,lemmitization,Stop words removal)
Tokentise the words

Create word frequency vector  

Use Logistic Regression for the classification

Check confusion matrix and get the accuracy
