## Note
nid: 1652345445637
model: Basic-02d89
tags: 05_neural_networks_bda
markdown: false

### Front
What is the idea behind <b>SeLU</b>?

### Back
\(\operatorname{selu}(x)=\lambda \begin{cases}x & \text { if }
x>0 \\ \alpha e^{x}-\alpha & \text { if } x \leqslant
0\end{cases}\) <b>Note:</b> Needs specific dropout (Alpha Dropout).
<b>Note 2:</b> SELU performs <b>internal normalization</b> (zero
mean, unit variance). Gradients are used to adjust the variance.
Scaling happens through the parameter \(\lambda\)
