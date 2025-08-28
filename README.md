

# Machine Learning Exercises

This repository contains my implementations of machine learning exercises, including algorithms and experiments learned in class. Each exercise includes code, explanations, and results when applicable.

---

##  Exercises

### Exercise 1 – Single Neuron Gradient Descent

**Description:**
Implement gradient descent based on the logistic loss function.

**Details:**

* Initialize weight vector **w = (0, …, 0)**
* Perform **T** update steps with learning rate **α**
* At each step, compute the total loss:

  $$
  J_t = \sum_i l_i
  $$
* Return:

  * Final weight vector **w**
  * Loss history **J = \[J1, …, JT]**
  * Weight history **w = \[w1, …, wT]**



### Exercise 2 – Backpropagation in a Multilayer Perceptron (MLP)

**Description:**
Implementation of gradient descent with **backpropagation** for a simple Multilayer Perceptron (MLP).

**Details:**

* Initialize network parameters (weights and biases).
* Forward pass: compute outputs layer by layer.
* Compute the loss function (e.g., logistic / cross-entropy).
* Backward pass: compute gradients using backpropagation.
* Update weights with gradient descent for **T** steps, using learning rate **α**.
* Track:

  * Loss history **J = \[J1, …, JT]**
  * Parameter updates (weights & biases over iterations).


