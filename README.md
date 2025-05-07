Scartch_NN
This is an implementation of classic neural networks using only numpy and scipy. This includes:
- Layers implementations (Sequential, Linear, Dropout, BatchNormalization, Conv2d, MaxPool2d)
- Activation functions (ReLU, LeakyReLU, ELU, SoftPlus, SoftMax, LogSoftMax)
- Objective functions(Losses) such as NLLLoss for both LogSoftMax and regular SoftMax
- Two optimizer algorithms (SGD, Adam)

To make sure that everything is correct test_modules notebook implements comparasion tests with pytorch.
Finally, supported by this implementation main_notebook implements full pipeline for MNIST dataset. As the result, a 95.6% accuracy was reached on test set.
