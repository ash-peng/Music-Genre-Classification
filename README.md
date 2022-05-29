# Music-Genre-Classification

This is a music genre classification project using a neural network. The chosen dataset is GTZAN, a data set famous for music classification.

First, we try to visualise ten 30-second pieces of music representative of their own musical styles (waveforms/spectrogram). The visualizations include an important feature for music distinguishing and classification - the zero crossing rate, which is the rate at which a signal transitions from positive to zero to negative or negative to zero to positive.

After that, we extract meaningful features, i.e. MFCCs, Spectral Centroid, Zero Crossing Rate, Chroma Frequencies, Spectral Roll-off, etc., from the music pieces. These are musical features which are known to be important for music genre classification. Once the features are extracted, they are appended into a CSV file so that a neural network of two hidden layers can be used for music classification.

The model is trained over 100 epochs with a batch size of 512. Train and test accuracies across epochs are also plotted.