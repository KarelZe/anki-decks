## Note
nid: 1626439531449
model: Basic-d7a3e-4ce08
tags: adv_ml::06_lecture
markdown: false

### Front
Give the central idea of the <b>nonlinear Principal Component
Analysis</b>?

### Back
Nonlinear PCA uses an inconsistency index as information criterion
to avoid overfitting in the choice of hyperparameters.
<div>
  Nonlinear PCA uses an autoassociative neural network for
  calculation of the PCAs. Autoassociative neural networks have one
  input layer, three hidden layers, and one output layer. One of
  the hidden layers is a socalled "bottleneck layer". The input
  layer and output layer have a size of the feature space.
</div>
<div>
  The network is trained to perform an identity mapping, where the
  input is approximated at the ouput.
</div>
<div>
  Since the number of hidden neurons in the middle hidden layer is
  restricted to the number of bottleneck neurons, which are fewer
  than the output neurons, one effectively calculates the principal
  components.
</div>
<div>
  The mean squared error (MSE) between the input layer and the
  output layer is mimized. In the process, the nonlinear principal
  components in the middle hidden layer, that is the bottleneck
  layer, are calculated.
</div>
