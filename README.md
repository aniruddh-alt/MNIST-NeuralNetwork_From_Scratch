# Feedforward Neural Network (FNN) for MNIST

This GitHub repository contains my implementation of a Feedforward Neural Network (FNN) trained on the MNIST dataset. FNNs are a type of simple Multilayer Perceptron (MLP) that process inputs through multiple hidden layers with activation functions. The network's weights and biases are optimized using forward and backward propagation to achieve the desired performance.

## Features

1. **PyTorch Implementation**  
   - A straightforward implementation of an FNN using PyTorch, achieving **96% accuracy** on the MNIST test dataset.
   - Utilizes PyTorch's `nn.Module`, `Dataset`, and `DataLoader` abstractions for efficient data management and model training.

2. **Hardcoded Neural Network**  
   - A step-by-step implementation of a neural network, explicitly detailing the mathematical formulas for:
     - Forward propagation
     - Loss computation
     - Backward propagation
   - This approach highlights the inner workings of an FNN, offering a deeper understanding of how these components interact.

3. **Custom Neural Network Framework**  
   - A replication of the PyTorch API to simulate the workflow of `nn.Module`, `Dataset`, and `DataLoader`.
   - This implementation showcases the fundamental design and principles of modern deep learning frameworks.

## Dataset

The [MNIST dataset](http://yann.lecun.com/exdb/mnist/) is used for this project. It contains:
- **Training data**: 60,000 handwritten digit images.
- **Test data**: 10,000 handwritten digit images.

Each image is a 28x28 grayscale pixel representation of digits (0-9).



## Results

- **PyTorch Implementation**: Achieved **96% accuracy** on the test dataset.
- **Hardcoded FNN**: Offers transparent insights into the training process, validating the fundamentals of backpropagation and optimization.
- **Custom API**: Mimics PyTorch's workflow, bridging the gap between abstract frameworks and low-level operations.


## Future Work

- Extend the implementation to include Convolutional Neural Networks (CNNs) for comparison.
- Experiment with additional optimizers and regularization techniques.
- Implement model evaluation on adversarial examples.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [PyTorch Documentation](https://pytorch.org/docs/)
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
- Tutorials and resources on neural networks and backpropagation.
