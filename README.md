# Shakespeare Text Generator Using LSTM

A character-level text generation model built with a **Long Short-Term Memory (LSTM)** neural network to generate Shakespeare-style text.

## Overview

This project explores recurrent neural networks (RNNs) for character-level language modeling. The LSTM learns sequential patterns, character dependencies, and stylistic features from a Shakespeare text to generate new text. (Definitely not an easy dataset for an RNN, not even for humans! ^^)

Text generation uses a **temperature of 0.2**, producing more deterministic and less random character sequences.

## Model Details

* **Architecture:** Long Short-Term Memory (LSTM): This model is inspired by how our memory works :D
* **Task:** Character-level text generation
* **Dataset:** Shakespeare text corpus
* **Sampling temperature:** 0.2
* **Framework:** TensorFlow / Keras

## How It Works

The model learns to predict the next character based on a sequence of preceding characters. During text generation, predicted character probabilities are adjusted using temperature scaling to control the randomness of the output.

A lower temperature, such as **0.2**, favors higher-probability characters, encouraging more predictable text generation.


## The Dataset
Btw, here is the dataset you can use for training your model: https://storage.googleapis.com/download.tensorflow.org/data/shakespeare.txt

## P.S.
You can definitely develop this model by changing the number of trained words, changing the temperature, and even changing the number of epochs.

And have fun!
