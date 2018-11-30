# An in depth review of LSTM based RNN in TensorFlow using MNIST
In __[this note book](https://github.com/meysamsadeghi/TF_mnist_LSTM/blob/master/tf_mnist_rnn.py)__ we implement a single layer LSTM based Recurrent Neural Network (RNN) classifier, for MNIST database of handwritten digits.

The __[note book](https://github.com/meysamsadeghi/TF_mnist_LSTM/blob/master/tf_mnist_rnn.py)__ organization is as follows. If you are just interested to see the code and dont care about details, jump to IV. RNN Implementation and The Code.

1. LSTM Based RNNs with TensorFlow
2. Basics of LSTM Based RNN
3. LSTM Based RNN in TensorFlow - A Closer Look into Details
    3.1. Static VS Dynamic RNN
    3.2. Important Notes on the shape of the input and outputs for RNN (tf.nn.dynamic_rnn)
    3.3. Using Dynam RNN Requires Caution if we have inputs with different length
    3.4. The Choice of LSTM Cell
4. MNIST Dataset Overview
5. RNN Implementation and The Code
