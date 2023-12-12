# Classifying-Disaster-Related-Tweets-as-Real-or-Fake
In this project I have analysed a dataset from Kaggle about disaster related tweets. I used Natural Language Processing(NLP) to classify these tweets as real or fake. 
I started by cleaning the data and creating a WordCloud of the `text` column in the dataset. 
I trained four different NLP models to classify the tweets. The accuracy scores achieved by these models were as follows:
1. Shallow Neural Network: train set accuracy of 0.59 and test set accuracy of 0.55
2. Multilayer deep text classification model: train set accuracy of 0.96 and test set accuracy of 0.77
3. Multilayer Bidirectional LSTM Model: train set accuracy of 99% and test set accuracy of 73
4. Transformer Model: train set accuracy of 0.97 and test set accuracy of 0.82

The data I used is available in my GitHub repository. However, it can also be obtained from this [Kaggle link](https://www.kaggle.com/competitions/nlp-getting-started/overview).
