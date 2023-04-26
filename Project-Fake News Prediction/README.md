Fake news prediction using Machine Learning

The spread of fake news on social media and other platforms is a serious worry because it has the potential to have a negative influence on society and the country. There has already been a lot of research to identify it. The research includes creating a supervised machine learning algorithm, that can classify fake news as true or false for English language texts by using tools like Python, Scikit- Learn, and NLP for textual analysis. This paper analyses the research on fake news detection and explores the best traditional machine learning models. We suggest using the Python sci-kit-learn module to do tokenization and feature extraction of this procedure, which will result in feature extraction and vectorization. In this paper, we proposed two machine learning algorithms decision tree and Multinomial Naive Bayes algorithms to classify the news articles. To tokenize the text TFIDF vectorizer is used. We have conducted the experimental analysis of the models and found that the Naive Bayes classifier outperformed the Decision tree model in terms of accuracy. The accuracy of the Naive Bayes classifier is 92 percent whereas the decision tree accuracy is 88 percent. Furthermore, the performance of the model is verified using precision, recall and F1 score by publishing the classification report. To conduct experimental analysis, we have used the publicly available news dataset that is collected from the Kaggle repository.

The main objectives of this project are:

•	Applying TF IDF text vectorizer in the data preparation step

•	Predicting the fake or legitimate news from the given input

The main features of this project are:
•	Applying Term frequency vectorizer to overcome the challenges of a Countvectorizer.

•	Count vectorizer gives the number of occurrences of the words in the document. If the sentences contain the stop words and other contexts of words automatically the weightage is given to the irrelevant words. Whereas the TFIDF vectorizer gives importance equally to the less frequent words and frequent words in the corpus.
 
