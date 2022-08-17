## Note
nid: 1656181862695
model: Basic-02d89
tags: 09_rl, 09_rl_bda
markdown: false

### Front
Why are correlations of Q-values and target values problematic?

### Back
The Bellman equation provides us with the value of \(Q(s, a)\) via \(Q\left(s^{\prime}, a^{\prime}\right)\) (this process is called bootstrapping). However, both the states \(s\) and \(s^{\prime}\) have only one step between them. This makes them very similar, and it's very hard for NNs to distinguish between them.

When we perform an update of our NN's parameters to make \(Q(s, a)\) closer to the desired result, we can indirectly alter the value produced for \(Q\left(s^{\prime}, a^{\prime}\right)\) and other states nearby. This can make our training very unstable, like chasing our own tail: when we update \(Q\) for state \(s\), then on subsequent states we will discover that \(Q\left(s^{\prime}, a^{\prime}\right)\) becomes worse but attempts to update it can spoil our \(Q(s, a)\) approximation, and so on.
