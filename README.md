# Neural-networks

![nn](https://user-images.githubusercontent.com/89722385/143810698-ab46fd57-52f0-40bd-b884-0ed397531ca3.jpeg)
<br>
Artificial neural networks (ANNs) are information processing systems that are
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
