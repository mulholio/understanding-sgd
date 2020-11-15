# Understanding SGD

This is a repo for practicing SGD with the `fastai` library. It models some madeup data as a quadratic function and then steps through, adjusting weights until it aproximates the data.

## Things I Learned

- All the steps for carrying out Stochastic Gradient Descent. 
- How gradient calculation works in PyTorch (`.requirese_grad` and `.backward()`, and `.grad`).
- Even if you are using SGD, you still need to decide on the form of the function you are optimising for e.g. a linear equation, cubic equation.
