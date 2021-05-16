# model
 A special form of recurrent neural networks (LSTM) is used to train a model which will classify the strategy in a given utterance, and generate a response acordingly just randomly selecting from human responses(not goal oriented). The model is implemented just  to gain an understanding and may be a baseline for the orijinal negotiation task.

 
# The dataset 
I will be using ‘casino_annotated.json’ which contains the dialogues tagged with strategies used in each utterance. The dataset is taken from https://www.kaggle.com/mathurinache/casino 


# project files

- casino_annotated.json – the dataset file

- lstm.ipynb – implementation of the lstm model as a baseline for the future negotiation task

- words.pkl – contains the words that contains a list of the vocabulary

- tags.pkl – contains the strategies tagged by experts

- model.h5 – trained seq2seq model which contains the info about the neural network created


inspired from https://github.com/SaifAlmaliki/Simple-Chatbot