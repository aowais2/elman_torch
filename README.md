# elman_torch
Elman implemented in PyTorch

Same concept as the other code. Two inputs and two outputs that signify (x,y) coordinates. Torch allows easier automatic gradient descent using the Autograd function.

Input is form 'a.csv'. The expected output is just the input one time step later. I.e. if output is y, and input is x,
y[n] = x[n+1]

This is to facilitate next time step prediction
