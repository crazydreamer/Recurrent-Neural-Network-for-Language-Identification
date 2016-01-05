# RNN based Language Identification


The first goal for Language identification is to build a classifier which can convert from a sequence of characters into a classification score for languages. Suppose that we have an input sequence x (text data) and a desired output is y (Language ID). For creation of training corpus, Leipzig corpus extracted and cleaned. Afterwards, each characters in sentences is mapped to unique character id. For RNN - LSTM architecture training, sequence of character ids  as inputs and output is class labels of language. We used 30K sentences for each language with 2 hidden layers of 200 nodes. It took 5 days to train the network with error rate of 3.48% for 9 European languages.
