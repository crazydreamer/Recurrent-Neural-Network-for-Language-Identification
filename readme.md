# RNN based Language Identification


The first goal for Language identification is to build a classifier which can convert from a sequence of characters into a classification score for languages. Suppose that we have an input sequence x (text data) and a desired output is y (Language ID). For creation of training corpus, Leipzig corpus extracted and cleaned. Afterwards, each characters in sentences is mapped to unique character id. For RNN - LSTM architecture training, sequence of character ids  as inputs and output is class labels of language. We used 30K sentences for each language with 2 hidden layers of 200 nodes. It took 5 days to train the network with error rate of 3.48% for 9 European languages.

# Prerquists

Install RNNLIB

# References

Alex Graves. Supervised Sequence Labelling with Recurrent Neural Networks
PhD thesis, July 2008, Technische Universität München

Sepp Hochreiter and Jürgen Schmidhuber Long Short-Term Memory
Neural Computation, 9(8):1735-1780, 1997

Language Identification: The Long and the Short of the Matter, Timothy Baldwin and Marco Lui

Graphme to phoneme conversion using Long short term memory Recurrent Neural Networks, Kanishka Rao, Fuchun Peng, Has ̧im Sak, Franc ̧oise Beaufays
