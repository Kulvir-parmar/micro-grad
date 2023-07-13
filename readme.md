# micro-grad

### What is this?

Micrograd is a tiny scalar-valued autograd engine and a neural net library on top of it with a PyTorch-like API. It operates over scalar values for backprop, e.g. we chop up each neuron into all of its individual tiny adds and multiplies. However, this is enough to build up entire deep neural nets doing binary classification, as the demo notebook shows.
Micorgrad is a great tool for learning about backpropagation and getting started with neural nets.
