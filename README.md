# ParentalDiscretionModel
Created own dataset using web mining and used NLP to classify sentences into 'viewable by small children' or 'parental discretion needed'. The model tries to learn words and patterns which are not suitable for small kids and thus any kid surfing the web should not view articles which contain demotivating, suicide-inducing, slander, murder or rape-related content.

1) Dataset train and Preprocessing:
  ● removed HTTP tags
  ● lowered the case
  ● removed all punctuation and Unicode
  ● removed stopwords
  ● lemmatization(converting a word into its root form considering the relevant Part of Speech associated with the word)
2) Got the top 10 and bottom 10 words and plotted them to get a sense of which words have greater impact on the model.
3) Embedding:
  ● Bag-of-words(frequency)
  ● TF-IDF(weight)
4) Split the data for test and train (15:85)
5) Built 4 classification Models namely:
  ● Random Forest Classifier,
  ● Adaboost Classifier,
  ● Gradient Boosting Classifier,
  ● Naive Bayes Classifier
6) Evaluated performance of each classifier based on:
  ● Confusion Matrix
  ● Accuracy Score
  ● Precision Score
  ● Recall Score
  ● Roc-Auc Score
