# Note
```
guid: d!H-tMnU>0
notetype: Basic-02d89-e0e22
```

### Tags
```
bda::05_neural_networks
```

## Front
What is the idea behind <b>SeLU</b>?

## Back
\(\operatorname{selu}(x)=\lambda \begin{cases}x & \text { if }
x>0 \\ \alpha e^{x}-\alpha & \text { if } x \leqslant
0\end{cases}\) <b>Note:</b> Needs specific dropout (Alpha Dropout).
<b>Note 2:</b> SELU performs <b>internal normalization</b> (zero
mean, unit variance). Gradients are used to adjust the variance.
Scaling happens through the parameter \(\lambda\)
