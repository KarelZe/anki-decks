## Note
nid: 1651487328480
model: Basic-02d89
tags: 02_basics_nn_dlcv
markdown: false

### Front
Explain the <b>Adagrad optimizer</b>.

### Back
Adapting the learning rates depending on weights.

Each weight \(\theta_{i}\) are modified with different learning rate, depending on the past gradients.

Weights with high gradients: learning rate reduced.
Weights with small gradient: learning rate increased.

\[
\theta_{t+1, i}=\theta_{t, i}-\frac{\eta}{\sqrt{G_{t, i i}+\epsilon}} \cdot g_{t, i} .
\]

\(G_{t, i i}\) is a diagonal matrix where element \(i, i\) is the sum of the squares of the gradients of the corresponding weight \(\theta_{i}\) up to time step \(t\)
