**FASHION MNSIT**<br><br>
The Notebook contains the code for creating a Machine learning model to classify the Fashion MNSIT dataset.
The Model is implemented using Convolutional Neural Networks and the Keras deep learning API.<br><br>
**CNN Layers**<br>
Sequential Keras API- linear stack of layers
1. Convolutional Layer - The layer has set of Independent Filters. These Filters when convolved over the Input Image produce Feature Maps.
2. Pooling Layer -  Used for Dimensionality Reduction or DownSampling the Input. It reduces the amount of Parameters and Computational power required drastically, thus reducing Overfitting. These along with Convolutional layer are able to learn more Complex features of the Image.
3. Batch Normalization - Zero mean and Variance one is achieved. It scales down outliers and forces the network to learn features in a distributed way, not relying too much on a Particular Weight and makes the model better Generalize the Images.
4. Flatten layer - Maps the input to a 1D vector
5. Output Layer - It has units equal to the number of classes to be identified.'softmax' activation function is used in case of Multi-Class Classification.
<br>

**Future work**<br>
-Using Data Augmentation on the input images to improve accuracy.<br>
-Implementing multiple Convolutional layers in the model.<br>
-Setting manual optimizer parameters.<br>
*Resource  - https://github.com/Chinmayrane16/Fashion-MNIST-Accuracy-93.4-*
