# LSTM-Penn-Treebank
LSTM Model on the Penn Treebank dataset to predict the next word in a sentence. It accomplishes this by finding the most probable word at each point in a sentence based on the previous context. The picture below displays an example where given the context "This is an" it finds the most probable susequent word. 

![alt text](http://i1380.photobucket.com/albums/ah175/nickwalker037/language-modelling_zpsqqkoijtn.png~original)

The model makes use of word embeddings for better processing. The loss is defined as the weighted cross-entropy loss and the model is trained using a gradient descent optimizer. 

The Repo consists of 2 files:
  - PTB_LSTM_StepByStep: This file breaks out the construction, training, and testing of the model into individual steps to better understand the steps Tensorflow takes to execute an LSTM model
  - PTB_LSTM: This file contains the final LSTM Model constructed from combining the individual steps in the other file into one class which runs the model


This model was contructed as part of the IBM Deep Learning Certification via edX
