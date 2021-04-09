# Music-Genre-Classification---Deep-Learning
Using Deep Learning Methods, we can use an End to End method (i.e. we can directly feed in wav files to the deep neural network) which will classify the song to 1 of 10 Genres from the GTZAN dataset. The architecture features a convolutional - bidirectional GPU architecture with dot product attention. The convolution layers allows spatial feature extraction, the bidirectional GRU allows classification for forward and backward sequential data, and the attention mechanism allows the architecture to focus on the segments of data deemed most appropriate.

We achieve a final accuracy of 86% and respectable accuracies for each individual genre. The model for this was based on ConflictNET: https://qmro.qmul.ac.uk/xmlui/handle/123456789/60041

Should you have any questions, please reach out.
