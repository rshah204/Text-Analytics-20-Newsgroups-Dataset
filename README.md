Text Analytics: 20 Newsgroups Dataset
----------------

Analysis of 20 Newsgroups Dataset Using Various Classification Models.

The goal of the project is to train different classifier and test the outcomes trying to achieve better accuracies. The appropriate classification algorithm with the optimal parameters will be selected to get best results. 

Refer to "User Instruction File.pdf" for brief instructions on how to set up and execute the python notebook.

• The 20 Newsgroup data is the collection of approximately 20,000 newsgroup documents, divided into 20 different newsgroups.
 
• Performed Exploratory Data Analysis followed by Data Cleaning which included, outlier treatment, corpus cleaning, removal of non-ascii characters, removal of stop words, stemming and lemmatization, generating unigrams and bigrams.

• Feature engineering techniques like TF-IDF Vectorizer and Count Vectorizer were used for tokenization in order to make the data ready for fitting the model.

• Used machine learning techniques to classify the documents into 20 different news groups. The data was trained over different classifiers such as Multinominal Naïve Bayes Model, Logistic Regression, Stochastic Gradient Descent Classifier, k Nearest Neighbors and Neural Networks.

• Various measures like accuracy, precision, recall and F-score were used to determine the best fit model.

• Classifiers Multinominal Naïve Bayes and k Nearest Neighbors performed best when neither stemming nor lemmatization was done and only unigrams were extracted in the TF-IDF Vectorizer.

• Logistic Regression had the best performance when Lemmatization was used with only unigrams extracted in the TF-IDF Vectorizer.

• Stochastic Gradient Descent Classifier had the best performance when Stemming was used with both unigrams and bigrams extracted in the TF-IDF Vectorizer.  Overall, this was the best performing model achieving an accuracy of 70.66%. 