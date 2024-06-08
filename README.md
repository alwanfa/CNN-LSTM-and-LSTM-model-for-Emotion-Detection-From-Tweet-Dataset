# CNN LSTM and LSTM model for Emotion Detection From Tweet Dataset
This repository contains a project focused on detecting emotions from Twitter datasets. The aim is to classify tweets into different emotion categories using machine learning and natural language processing (NLP) techniques.
Project Description

The goal of this project is to develop a system that can accurately identify and classify emotions expressed in tweets. This can be useful for sentiment analysis, market research, and understanding public opinion on various topics. The project involves preprocessing the text data, training various machine learning models, and evaluating their performance.

## Dataset
The dataset used in this project consists of emotion labeled tweets taken from https://github.com/Ricco48/Emotion-Dataset-from-Indonesian-Public-Opinion. The dataset consists of 6 emotions including Anger, Joy, Sadness, Fear, Surprise, Disgust.

## Preprocessing
Preprocessing data includes
- removing punctuation
- normalizing laughing word exaggeration in prefix and postfix of the word with dictionary method using.
- normalizing colloquial Indonesian dataset using dictionary method from https://github.com/nasalsabila/kamus-alay dataset.
- POS Tagging using https://huggingface.co/w11wo/indonesian-roberta-base-posp-tagger
- Word Embedding using Fasttext https://fasttext.cc/ Embedding Matrix on Embedding Layer

  The Code is in the inference.ipynb on function pipeline section

## Model
  In this project there are 2 model trained including LSTM and CNN-LSTM. Hyperparameter tuning using hyperband tuning.
  ### LSTM
  ![image](https://github.com/alwanfa/CNN-LSTM-and-LSTM-model-for-Emotion-Detection-From-Tweet-Dataset/assets/71076451/0beab914-0995-4dce-94f8-5cf45006bf9b)

  ### CNN-LSTM
  ![image](https://github.com/alwanfa/CNN-LSTM-and-LSTM-model-for-Emotion-Detection-From-Tweet-Dataset/assets/71076451/1dc154bd-5514-4ab1-bb4e-27f69113fe9f)


