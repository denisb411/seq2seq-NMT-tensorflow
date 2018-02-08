# Neural Machine Translation using Tensorflow's seq2seq

*This project uses Tensorflow 1.4 for the seq2seq implementation (tensorflow.contrib.seq2seq).*

This project was highly based on tensorflow's nmt model (https://github.com/tensorflow/nmt) and on Language-Translator-RNN (https://github.com/jamesrequa/Language-Translator-RNN) for the preprocessing and help code.

This project implements de following mechanisms:

- BeamSearch at the inference mode
- Bidirectional LSTM Encoder
- Attention mechanism (seq2seq.BahdanauAttention)
- Learning rate exponential decay through time

It was used a fr/en dataset, which trained the model to translate french sentences to english.
