Recurrent neural networks
=========================

## Definition

The main feature of an RNN is its hidden state, which captures some information about a sequence.
the same task for every element of a sequence
has a “memory”
shares the same parameters (U, V, W) across all steps

## Differneces

- DNN: all inputs (and outputs) are independent of each other
- RNN: the output being depended on the previous computations

## Model

y = model.next_step(x, R)

- y - output
- x - input
- R - memory

## LSTM = Long Short-Term Memory

have a different way of computing the hidden state R

are much better at capturing long-term dependencies than vanilla RNNs are

## Backpropagation (Backprop)

is a method to calculate the gradient of the loss function.
used, for example, in the gradient descent algorithm

## BPTT = BackPropagation Through Time
