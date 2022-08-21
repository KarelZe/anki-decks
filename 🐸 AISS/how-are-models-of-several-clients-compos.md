## Note
nid: 1646669148311
model: Basic-02d89
tags: 06_systemwide_learning
markdown: false

### Front
How are models of <b>several clients</b> composed in <b>federated
learning</b>?

### Back
Process is called <b>federated averaging</b>.

To combine the updates of each client, a fusion model is needed. An example is federated averaging.

Combines local stochastic gradient descent (SGD) on each client with a server that performs model averaging. 

As the data is imbalanced (distribution and size) local models are aggregated by weighting each local model by the number of available training samples. Thus clients with more data have more influence on aggregated model.

<img src="83387597.png">
