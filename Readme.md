# Data Structure Assignment1: Learning XOR operations using "neural-like networks" (need to include hidden layers)
## Introduction
In this process, you can train the system with some training data,than input testing data,the system can output the answer of XORoperations.

## Steps

1. Enter the number of Layers in Neural Network
   ```c
    Enter the number of Layers in Neural Network:
    4
    ```
2. Enter the number of neuron in each layers
    ```c
    Enter number of neurons in layer[1]: 
    2
    Enter number of neurons in layer[2]: 
    4
    Enter number of neurons in layer[3]: 
    4
    Enter number of neurons in layer[4]: 
    1
    ```
3. Than the  screen will show is layers and neurons created successfull
    ```c
    Created Layer: 1
    Number of Neurons in Layer 1: 2
    Neuron 1 in Layer 1 created
    Neuron 2 in Layer 1 created

    Created Layer: 2
    Number of Neurons in Layer 2: 4
    Neuron 1 in Layer 2 created
    Neuron 2 in Layer 2 created
    Neuron 3 in Layer 2 created
    Neuron 4 in Layer 2 created

    Created Layer: 3
    Number of Neurons in Layer 3: 4
    Neuron 1 in Layer 3 created
    Neuron 2 in Layer 3 created
    Neuron 3 in Layer 3 created
    Neuron 4 in Layer 3 created

    Created Layer: 4
    Number of Neurons in Layer 4: 1
    Neuron 1 in Layer 4 created
    ```
4. If everything all right, enter the [learning rate](https://en.wikipedia.org/wiki/Learning_rate) (usually be 0.15).
    ```c
    Enter the learning rate (Usually 0.15): 
    0.15
    ```
5. Enter the number of training examples
    ```c
    Enter the number of training examples: 
    4
    ```
6. Enter the Inputs for training examples.(Follow the truth tabke of XOR logic gate)
    Input | output
   -------|--------
     0 0|0
     0 1|1
     1 0|1
     1 1|0
    ```c
    Enter the Inputs for training example[0]:
    0 0

    Enter the Inputs for training example[1]:
    0 1

    Enter the Inputs for training example[2]:
    1 0

    Enter the Inputs for training example[3]:
    1 1
    ```
7. Enter the Desired Outputs (Labels) for training examples
    ```c
    Enter the Desired Outputs (Labels) for training example[0]: 
    0

    Enter the Desired Outputs (Labels) for training example[1]: 
    1

    Enter the Desired Outputs (Labels) for training example[2]: 
    1

    Enter the Desired Outputs (Labels) for training example[3]: 
    0
    ```
8. Our Neural Network will be trained on these 4 training examples for 20000 epochs.
9.  Now, you can test the trained Neural Network
    ```c
    Enter input to test:
    0 0
    Output: 0
    ```
## References
    *https://speech.ee.ntu.edu.tw/~hylee/ml/2019-spring.php
    *https://medium.com/analytics-vidhya/building-neural-network-framework-in-c-using-backpropagation-8ad589a0752d
    * https://ithelp.ithome.com.tw/markdown