# AI2-project3

### Project description

Develop a sentiment classifier using a bidirectional stacked RNN with LSTM/GRU cells
for the Twitter sentiment analysis dataset. For
the development of the models, you can experiment with the number of stacked RNNs,
the number of hidden layers, type of cells, skip connections, gradient clipping and dropout
probability. Document the performance of different configurations on your final report.
Use the Adam optimizer and the binary cross-entropy loss function. Remember to transform the predicted logits to probabilities using a sigmoid function. You should also utilize
pre-trained word embeddings (GloVe) as the initial embeddings to input on your models.
For the best model you found:

* Compute precision, recall and F1 for each class.
* Plot the loss vs. epochs curve and the ROC curve and explain what you see.
* Compare with your best model from Homework 2.

### Files of the project

* In the file Question-1.ipynb, I implemented three models of a sentiment classifier - simple RNN, LSTM & GRU - and I experimented with different parameters.
* In the file Best-model.ipynb, is the presentation of the best model of the experiments in the file above. A ROC curve is added.   
