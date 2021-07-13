# Fake-News-Classifier
The Dataset if from one of Kaggle compettions link = https://www.kaggle.com/c/fake-news/overview

### The Contents of Dataset :
  1. Train.csv = File on which training of the model is being done.
  2. Test.csv = File for testing the model.

## Mode modeling

### 1. NLP(Natural Language Processing)
This is one the most profound way of modelling the test based model such that system could understand
Library Used:
  1. NLTK is a leading platform for building Python programs to work with human language data. For more explanation you could read the official page = https://www.nltk.org/.
  2. Stopwords is are those words that most of time doesn't add any significance any kind of review or recomandation model. For more explanation refer wikipedia page = https://en.wikipedia.org/wiki/Stop_word.
  3. The Stemmer used for this model is PortStemmer. https://pypi.org/project/PorterStemmer/ the official link for more information.
  4. TFIDF, short for term frequency–inverse document frequency, is a numerical statistic that is intended to reflect how important a word is to a document in a collection or corpus. For imformation refer the wikipedia page = https://en.wikipedia.org/wiki/Tf%E2%80%93idf
  5. CountVectorizer is the another or official name of Bag of Words its like the name suggest in this the words are depicted in multiset of words disgarding the grammer and even repeated words

### 2. LSTM(Long Short-Term Memomery)

It's an ANN(Artificial Neural Network) unlike standard feedforward neural network , it has feedback connections. A comman LSTM unit is campared of a cell , an input gate , an output gate and forget gate. The cell remembers values over arbitrary time intervals and the three gates regulate the flow of information into and out of the cell.
