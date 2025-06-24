# Next-Word-Prediction-Using-Word-Level-LSTM-on-Shakespearean-Text
Developing an AI model to predict next words of a text - Trained Tensorflow's Sequential model on Shakespearean text.

# Features - Images here
Uses an LSTM model trained on Shakesperian text
Uses word-level tokenization for deeper semantic understanding.
Includes recording model efficiency over different number and type of lstm layers
Includes loss graphs
Saves the most efficient model for later use
demo: predicts next word in a sentence

restrictions: 
old english
at least first 13 words of the sentence should be priovided as prompt

# Installation and Setup
1. Clone the repository
git clone https://github.com/RJ601/Next-Word-Prediction-Using-Word-Level-LSTM-on-Shakespearean-Text.git
cd Next-Word-Prediction-Using-Word-Level-LSTM-on-Shakespearean-Text

# Usage
To test the model on custom input:
python demo.py

image

# Tools, Libraries and Dataset used
Language: Python 3.9.23

Libraries:
keras                        3.10.0
scikit-learn                 1.6.1
tensorflow                   2.19.0
matplotlib                   3.9.4
numpy                        2.0.2
pandas                       2.3.0
nltk                         3.9.1

Dataset: Shakespeare Plays dataset from Kaggle.

# License
