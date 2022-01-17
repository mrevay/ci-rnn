# ci-rnn
This repository contains the code for running the experiments from the following paper:  
[Contracting Implicit Recurrent Neural Networks: Stable Models with Improved Trainability](http://proceedings.mlr.press/v120/revay20a.html)

We construct simple conditions that guarantee contraction in recurrent neural networks. The conditions take the form of a semidefinite constraint which we impose using the [Burier-Monteiro](https://papers.nips.cc/paper/2016/hash/3de2334a314a7a72721f1f74a6cb4cee-Abstract.html) approach to semidefinite programming. This results in a nonlinear equality constrained optimization problem that we solve using an augmented Lagrangian method.

We demonstrate the method on a simple simulated nonlinear example, and on a real gait prediction task.
