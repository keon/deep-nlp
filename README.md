# deep-nlp
Deep Learning for Natural Language Processing in PyTorch

This tutorial covers the basic deep learning algorithms that are used in nlp with minimal dataset (like a sentence or two).
The tutorials assume that you know nothing about nlp or deep learning. You just need to know some Python.

## [Basics](./00-basics)

You might have seen similar examples from somewhere else.
These are the machine learning basics you have to go through in order to understand the following contents.

- [Linear Regression](linear-regression.ipynb)
- [Logistic Regression](logistic-regression.ipynb)
- [Neural Network](neural-network.ipynb)

## [Word Vectors](./01-word-vectors) (aka word embeddings)

- [Word2Vec](./01-word-vectors/word2vec.ipynb)
- [GloVe](./01-word-vectors/glove.ipynb)

## [Recurrent Neural Network](./02-recurrent-neural-net)

Let's implement Recurrent Neural Network and their variants from scratch.

- [Recurrent Neural Network (RNN)](./02-recurrent-neural-net/rnn.ipynb)
- [Long Short Term Memory (LSTM)](./02-recurrent-neural-net/lstm.ipynb)
- [Gated Recurrent Unit (GRU)](./02-recurrent-neural-net/gru.ipynb)


## [Text Generation](./03-text-generation)

You can generate sentences using RNN.

- [Sentence Generation with RNN](./03-text-generation/text-generator.ipynb)

## [Text Classification](./04-text-classification)

- [Text classification with CNN](./04-text-classification/cnn-classifier.ipynb)
- [Text classification with RNN](./04-text-classification/rnn-classifier.ipynb)
- [Text classification with RNN + Attention](./04-text-classification/rnn-attention-classifier.ipynb)

## [Sequence-to-Sequence](./05-Sequence-to-Sequence) (Seq2Seq)

Think about how you make a response to a text. First, you interpret what the sentence is (classification) and generate your answer from start to finish.
Since we know how to build text classifier and text generator, would it make sense for us to use both of them at the same time? Yes!
Merging text classifier with text generator gets you a mini translator!

- [Encoder Decoder](./05-sequence-to-sequence/encoder-decoder.ipynb)
- [Seq2Seq with Attention Mechanism](./05-sequence-to-sequence/seq2seq-attention.ipynb)

## [Question Answering](./06-question-answering)

What if the sentence given is a question? You cannot answer a question by just based on that question. You need knowledge.
We memorize stuffs from our experiences. Those can be given by teachers, news papers, and etc.
Then we answer to the question based on what we've seen, read, or heard.
Now instead of spitting out a nonsensical sentence, lets make it memorize some stuffs.

- [Memory Networks](./06-question-answering/memory-networks.ipynb)
