# RNN-model

- Recurrent neural network is a type of neural network in which the output form the previous step is fed as input to the current step
- In traditional neural networks, all the inputs and outputs are independent of each other, but this is not a good idea if we want to predict the next word in a sentence
- We need to remember the previous word in order to generate the next word in a sentence, hence traditional neural networks are not efficient for NLP applications
- RNNs also have a hidden stage which used to capture information about a sentence
- RNNs have a ‘memory’, which is used to capture information about the calculations made so far

![image](https://github.com/Siddhipatade/RNN-model/assets/91780318/071cd48f-e523-4882-96ab-4dc23250a24a)

#### Advantages:
- An RNN remembers each and every information through time. It is useful in time series prediction only because of the feature to remember previous inputs as well. This is called Long Short Term Memory.
- Recurrent neural network are even used with convolutional layers to extend the effective pixel neighborhood.
#### Disadvantages:
- Gradient vanishing and exploding problems.
- Training an RNN is a very difficult task.
- It cannot process very long sequences if using tanh or relu as an activation function.

