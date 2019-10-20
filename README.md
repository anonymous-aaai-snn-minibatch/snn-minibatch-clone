# Minibatch Processing in SNNs

This repository accompanies the paper draft of the same name.

## Setting up

This project was developed with Python 3.6.

Clone the repository and navigate to the project's root directory. Then, issue:

```
pipenv install --skip-lock  # Create pipenv virtual env.
pipenv shell  # Launch shell in virtual env.
```

## Key Files

```
minibatch/conv_mnist.py
```
This file provides the training used to show that the features we learned are consistent regardless of the batchsize.

```
minibatch/scaling/scaling.py
```
This file provides the generators of the timing and accuracy metrics as they relate to batch size.
