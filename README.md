# Neural-networks

![nn](https://user-images.githubusercontent.com/89722385/143810698-ab46fd57-52f0-40bd-b884-0ed397531ca3.jpeg)
<br>
<b>Artificial neural networks (ANNs)</b> are information processing systems that are
modeled on and inspired by the human brain, which they try to mimic by learning
how to recognize patterns in data. They accomplish tasks by having a well structured
architecture. This architecture is composed of several small processing units called
neurons, which are interconnected in order to solve major problems.<br><br>
These algorithms work by taking all of the data as input, in which the first layer of
neurons acts as the input. After that, every entry is passed to the next layer of neurons,
where these are multiplied by some value and processed by an activation function,
which makes "decisions" and passes those values to the next layer. The layers in the
middle of the network are called hidden layers. This process keeps going until the
last layer, where the output is given. When introducing the MNIST images as input
to the neural network, the end of the network should have 10 neurons, each neuron
representing each digit, and if the neural network guesses that an image is a specific
digit, then the corresponding neuron will be activated. The ANN checks whether it
has succeeded for the decision, and if not, it performs a correction process called
backpropagation, where every pass of the network is checked and corrected, adjusting
the weights of the neurons.
 
Important: <br>

<b>Normalized Data:</b>
<br>Having normalized data means converting that 0-255 range of values to a range of
0-1. The values must be adapted to fit between 0 and 1, which means they will be float
numbers, because there is no other way to fit a higher range of numbers into a shorter
range So, first we need to convert the data to a float and then normalize it.

<b>One-hot-encoding:</b><br>
transforms the number of the digit of every label to one-hot encoding, In order to do that, we need to use a function from Keras, from its utils package (the name has changed to np_utils), called to_categorical().

<br>
<b>Activation Function:</b><br>
For a basic neural network, dense layers (or fully connected layers) are employed.
These neural networks are also called fully connected neural networks. These contain
a series of neurons that represent the neurons of the human brain. They need an
activation function to be specified. An activation function is a function that takes the
input and calculates a weighted sum of it, adding a bias and deciding whether it should
be activated or not (outputs 1 and 0, respectively).The sigmoid and ReLU functions calculate the weighted sum and add the bias. They then output a value depending on the value of that calculation. The sigmoid function
will give different values depending on the value of the calculation, from 0 to 1. But
ReLU will give 0 for negative values or return the value of the calculation for positive
values.<br><br>
Toward the end of a neural network, normally the softmax activation function takes
place, which will output a non-probabilistic number for every class, which is higher for
the class that has the highest chance of corresponding to the input image. There are
other activation functions, but this one is the best for the output of a network for multi-
classification problems.<br> <br>
