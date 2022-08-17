## Note
nid: 1651474119943
model: Basic-02d89
tags: 02_basics_nn_dlcv
markdown: false

### Front
Explain the main concept of <b>classic</b> / <b>Batch Gradient
Descent</b>.

### Back
In <b>Batch Gradient Descent</b>, we try to minimize
\(L(\theta)=\sum_{i=0}^{n} L_{i}(\theta)\) with parameters
\(\boldsymbol{\theta}\), a training dataset with \(n\) examples and
\(L_{i}\) depicting the loss for the \(i\)-th example.
<b>Intuition:</b> We build a full sum over all examples to update
\(\theta\).
