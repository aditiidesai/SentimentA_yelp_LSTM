# SentimentA_yelp_LSTM

Binary Sentiment Analysis using LSTMs
Dataset: Yelp dataset

NLP Sentiment Analysis steps:
data collection, preprocessing( tokenization, removing stopwords etc), text vectorization, LSTM RNN model, test

RNN is they cannot remember long-term dependencies due to vanishing gradient. LSTMs are explicitly designed to avoid long-term dependency problems.

loss = 'categorical_crossentropy', optimizer='adam',metrics ='accuracy'
Embedding Layer in Keras is a simple yet powerful tool that transforms positive integers (indexes) into dense vectors of fixed size. It's often used to process text data in NLP tasks, where words are converted into corresponding dense vectors

https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9716923
