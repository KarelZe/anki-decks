## Note
nid: 1656172546495
model: Basic-02d89-e0e22
tags: bda::09_rl
markdown: false

### Front
What is the <b>idea </b>behind the <b>Categorical DQN</b>?

### Back
Predict a distribtuon of values for every action as a simple value might not be the best representation of the expected results.

Requires the Bellman Equation to be generalized for distributions:
\(Z(x, a) \stackrel{D}{=} R(x, a)+\gamma Z\left(x^{\prime}, a^{\prime}\right)\)
