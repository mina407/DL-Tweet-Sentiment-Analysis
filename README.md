# Sentiment Analysis using Bidirectional LSTM

**Project Overview**
This project implements a Bidirectional LSTM model for sentiment analysis. The model classifies text into positive, negative, or neutral sentiment.

**Dataset**
[Dataset is Twitter Comments,shape is 27482 Rows 4 Columns, format :- .csv]

**Model Architecture**
* Embedding layer with a vocabulary size of 5000 and embedding dimension of 100.
* Bidirectional LSTM layer with 128 units.
* Dense layer with softmax activation for classification.

**Training**
The model is trained using the Adam optimizer with a learning rate of 0.01 and sparse categorical crossentropy loss. Early stopping is implemented to prevent overfitting.

**Dependencies**
* Pandas - Numpy - Matplotlib - sklearn - imblearn
* TensorFlow/Keras

**Results**
Macro_precision is 0.843
Macro_recall is 0.837
Macro_f1 is 0.83
