# named-entity-recognition
This is a named-entity-recognition (NER) project which I did when I took CSCI544 Applied Natural Language Processing in Fall 2021 at USC.

For this project, I applied deep learning techniques to train a classifier on NER tasks. Specifically, I built a bidirectional LSTM model which included one embedding layer, one lstm layer and two linear layers. For word vectorizations, I tried both starting from one-hot vectors and directly using the pretrained GloVe model.

The one-hot-vector-based model was trained for 120 epochs, and the validation results on the dev data were as follows:

![one_hot](https://user-images.githubusercontent.com/90494164/174703270-147c78cb-a8b0-408d-8160-98b30dddfbac.png)

The GloVe-based model was trained for 80 epochs, and the validation results on the dev data were as follows:

![glove](https://user-images.githubusercontent.com/90494164/174703289-bfbc9031-4df6-457f-b4d6-812e25c9a46d.png)
