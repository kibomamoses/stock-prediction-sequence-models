# stock-prediction-sequence-models


Sequential for initializing the neural network
Dense for adding a densely connected neural network layer
LSTM for adding the Long Short-Term Memory layer
Dropout for adding dropout layers that prevent overfitting
then added the LSTM layer and later added a few Dropout layers to prevent overfitting. I added the LSTM layer with the following arguments:

50 units which is the dimensionality of the output space
return_sequences=True which determines whether to return the last output in the output sequence, or the full sequence
input_shape as the shape of our training set.\
I fitted the model to run on 25 epochs with a batch size of 32.
