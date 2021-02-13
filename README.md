# Classifying the MNIST dataset with a neural network using PyTorch.

This notebook contains sample code for classification of the MNIST dataset with a basic neural network using PyTorch. It experiments on the effects of i)the number of layers, ii)the activation function used, on the overall accuracy of the classifer. Note, that I have limited the number of epochs to 50 since the aim here is to make a comparison between different models and not to achieve the optimal accuracy. Number of epochs can be increased to further improve the accuracy. Below is a summary of the findings. It plots the comparisons between the losses of the different models.


## Comparison between a single layer network and a two layered network with a ReLU activation function.
<p align="center">
![alt text](https://github.com/jazibeijaz1/classifying-mnist-dataset-with-neural-network/blob/main/images/image1-copy.png?raw=true)
</p>

- Accuracy for single layer network: 92.1%
- Accuracy for two layered network with ReLU activation function: 97.0%



## Comparison between a two layered network and a three layered network, both with ReLU activation functions.

![alt text](https://github.com/jazibeijaz1/classifying-mnist-dataset-with-neural-network/blob/master/images/image2.png?raw=true)

- Accuracy for two layered network: 97.0%
- Accuracy for three layered network: 97.7%



## Comparison between a three layered network(Sigmoid Activation) and a three layered network(ReLU Activation).

![alt text](https://github.com/jazibeijaz1/classifying-mnist-dataset-with-neural-network/blob/master/images/image3.png?raw=true)

- Accuracy for three layered network(Sigmoid): 91.0%
- Accuracy for three layered network(ReLU): 97.7%


## Additional Notes
- Accuracy for two layered network without any activations: 92.3%
- Accuracy for two layered network with Sigmoid as activation function: 92.4%


## Conclusions
- Increasing the number of layers improves the overall accuracy of the model.
- Increasing the number of layers improves the overall accuracy of the model, even if no activation function is applied. Though the improvement is minor.
- ReLU works significantly better than sigmoid.
