# a_i_neural_networks
Defining a bunch of neural networks

The first artificial neural network was the "perceptron", 
which was developed by Frank Rosenblatt in 1957. The 
perceptron was a type of feedforward neural network that 
was designed to learn from input data and make binary 
classifications. It consisted of a single layer of 
artificial neurons that received inputs, computed a 
weighted sum, and produced an output. The perceptron was 
an important milestone in the history of neural networks, 
and its development marked the beginning of a new field of 
research in artificial intelligence.

Here is an illustration of a simple perceptron:

      w1
     /   \
x1 -o     o- y
     \   /
      w2
      
In this diagram, x1 represents the input to the perceptron, 
w1 and w2 are the weights associated with the inputs, and y 
is the output of the perceptron. The perceptron computes the 
weighted sum of its inputs as:

z = w1*x1 + w2*x2

and applies an activation function, typically a step function 
such as the Heaviside step function, to produce the output y:

y = f(z)

&

The Heaviside step function, also known as the unit step function, 
is a mathematical function that takes a real number as input and 
produces a binary output of 0 or 1. The function is defined as:

H(x) = {0 if x < 0
        1 if x >= 0}

The perceptron learning algorithm adjusts the weights w1 and w2 based 
on the error between the desired output and the actual output, in order 
to minimize the error over a set of training examples. This allows the 
perceptron to learn to make binary classifications based on input data.



The perceptron has evolved into several other types of neural networks. One of the most notable developments was the multi-layer perceptron (MLP), which was introduced in the 1960s and consists of multiple layers of artificial neurons. MLPs are able to learn more complex functions than the original perceptron and have been used for a wide range of applications, such as image recognition, speech recognition, and natural language processing.

Another important development that built on the perceptron was the backpropagation algorithm, which was introduced in the 1970s and enables neural networks to learn from examples by adjusting the weights of the connections between neurons. Backpropagation made it possible to train multi-layer perceptrons and other types of neural networks, and it played a key role in the resurgence of neural networks in the 1980s and 1990s.

Today, the perceptron is still used as a building block for many other types of neural networks, and its basic architecture and learning rules have been extended and modified in many different ways to enable more powerful and sophisticated neural network models.
