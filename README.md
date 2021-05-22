# Image-Captioning
Encoder Decoder Model for Image Captioning

# Encoder Model
For extracting the feature vectors from the image, a CNN based model is used. Pytorch trasfer learning using GoogleNet model was used for this purpose. The size of the model is 49MB.
The feature vector is then converted to a particular embedding size for input to the Decoder model

# Decoder Model
After the feature vectors are obtained with embed size, we feed this vector along with the actual captions to a LSTM model for training. The captions also need to be converted to embed size so as to match the input size of the LSTM.

# Model
The Encoder-Decoder model is 15 epochs trained and the number of parameters is 12 million.