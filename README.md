# LSTM Network From Scratch (Text Generation & Image Classification)

## Description

**Long Short Term Memory (LSTM)** networks are a modified version of Recurrent Neural Network (RNN) which allow information to persist to the next stage. The LSTM network is capable of learning order dependence in sequence prediction problems and also mitigating the vanishing gradient problem faced by traditional RNN models.

LSTMs are a complex area of deep learning, and it is widely used in complex problem domains like speech recognition, language translation, self driving cars, automated traidings, image recognition in many more. In this project implemented text generation and MNIST handwritten digit classification models using LSTM network from scratch.

## Text Generation

- LSTM Text Generation Project File: [Text Generation Notebook](https://github.com/PNilay/LSTM-Network-from-Scratch/blob/main/Text%20Generation/Text_Generation_LSTM_V2.ipynb)

Text Generation is a subfield of natural language processing (NLP), which is the ability of computers to understand human languages as it is spoken and written. NLP uses knowledge in artificial intelligence, computational linguistics and computer science to intuitively generate natural language texts, which can fulfill certain requirements. Text generation, speech to text, translation system, text summarization and sentiment analysis are some of the popular NLP problems.

**Text generation is the task of producing new text with the intention to bear a resemblance to human-written text.** Text generation model is trained using sample input and outputs to learn probabilities about what character will come next in a sequence. A trained text generation model predicts the next character based on the previous sequence of characters used in the text. Language generation model can be operated at character level, word level, sequence level or even paragraph level.

In this project, a character level text generation model is implemented and trained using LSTM neural network for generation of natural language text.

### Three Important layers of text generation model:
  1. Input layer: Takes the one-hot-encoding of a character as input
  2. LSTM Layer: Computes the output using LSTM units. Multiple layers of LSTM blocks can be added in the model to improve text generation accuracy.
  3. Output Layer: Computes the probability of the best possible next character in the sequence

## Image Classification (MNIST Digits Classification)
