# Pure-CNN

1. Data Loading: The MNIST dataset is loaded, which consists of handwritten digit images along with their corresponding labels. The dataset is split into training and testing sets.

2. Data Preprocessing: The pixel values of the images are normalized to the range [0, 1]. The input images are reshaped to match the expected input shape of the CNN models.

3. Model Definition: The CNN model is defined using either PyTorch or TensorFlow. The model architecture typically consists of convolutional layers followed by fully connected layers, and the appropriate activation functions are applied.

4. Model Compilation: The model is compiled with an optimizer and a loss function . Additional metrics for evaluation can be specified.

5. Model Training: The model is trained on the training dataset using batches of data. The training loop iterates over the specified number of epochs, with each batch being passed through the model. The optimizer calculates gradients and updates the model parameters based on the defined loss function.
