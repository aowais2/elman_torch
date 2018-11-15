# elman_torch
Elman implemented in PyTorch

Same concept as the other code. Two inputs and two outputs that signify (x,y) coordinates. Torch allows easier automatic gradient descent using the Autograd function.

Input is fromm 'a.csv'. The task is to train the network to follow the figure Infinity drawn, with the co-ordinates as given in a.csv

The expected output is just the input one time step later. I.e. if output is y, and input is x,
y[n] = x[n+1]
This is to facilitate next time step prediction
