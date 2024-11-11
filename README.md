# Deep-Learning-Course

--------------------------- LAB MLP ---------------------------
Implementation of multilayer perceptrons (MLPs) for different classification tasks.

The first part is an MLP model applied to the XOR function, a classic example to showcase neural networks' ability to learn non-linear relationships. The model has one hidden layer with 2 neurons, using the ReLU activation function and the Adam optimizer. After training on the XOR inputs, the model outputs predictions, calculates accuracy, and displays weights and biases of the network layers.

The second part involves an MLP for the MNIST digit classification task. This model includes two hidden layers with 128 and 64 neurons, both using ReLU, and a 10-neuron output layer with a softmax activation for multi-class classification. The model is compiled with `categorical_crossentropy` loss and the Adam optimizer, trained over 5 epochs, and evaluated for accuracy on the test set, demonstrating its ability to handle complex, large-scale data.



--------------------------- LAB CNN 1 ---------------------------

MNIST Image Classification with CNN
This project uses a Convolutional Neural Network (CNN) to classify handwritten digits (0-9) from the MNIST dataset, achieving about 98% accuracy on test data. The model architecture includes Conv2D and MaxPooling layers for feature extraction, followed by Flatten and Dense layers for classification.

- **Conv2D** : 32 filtres, noyau 3x3, activation ReLU
- **MaxPooling2D** : taille de pool 2x2
- **Flatten** : mise à plat des données
- **Dense** : 128 neurones, activation ReLU
- **Sortie Dense** : 10 neurones (softmax pour classification)


------------------------- LAB CNN 2 --------------------
Same as LAB CNN 1 but with addded dropout LAyer 
