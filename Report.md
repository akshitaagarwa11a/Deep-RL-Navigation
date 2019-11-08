# Conclusion
In this article, I discuss the training result of the implemented DQN Agent

## Learning Algorithm
As input a vector (size 37) is used instead of the image so no convolutional layer is need. 
The following deep neural network has following layers:</br>

* Fully connected Linear layer - input 37 - output 64</br>

* Fully connected Linear layer - input 64 - output 64</br>

* Fully connected Linear layer - input 64 - output 64 (action_size)</br>

* Linear Activation Function were used</br>

* Adam Optimzer was used to caluclate loss

## Epsilon Greedy
An epsilon-decreasing strategy was used.

## DQN
Utilizing a second “target” network, which we will use to compute target Q-values during our updates.

Δw=α(R+γ·max ô(S',a,w'); - ô(S,A,w)) ∇w o(S,A,w)

with w' fixed target value during training. Are only updated with the Q-network parameters everc C steps ( here C = 4 )

## Experience Replay
Fixed-size buffer to store experience tuples

## Hyperparameters
* Replay Buffer size - BUFFER_SIZE = int(1e5)
* Minibatch size - BATCH_SIZE = 64
* Discount factor - γ = 0.99
* For soft update target parameters - τ = 1e-3
* learning rate - lr = 5e-4
* how often network is updated - C = 4
## Results
The required criterion of an average of 13 points was achieved in less than 500 episodes.

