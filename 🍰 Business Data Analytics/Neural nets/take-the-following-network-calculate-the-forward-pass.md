# Note
```
guid: cS]jE1FTgo
notetype: Basic-02d89-e0e22
```

### Tags
```
bda::05_neural_networks
```

## Front
Take the following network. Calculate the forward pass. <img src="paste-2ca4e4766e653e28a47842063a57ccf30bb665fc.jpg">

## Back
<b>Computations:</b> \[\begin{gathered} Z^{[1]}=W^{[1]} x+b^{[1]}
\\ a^{[1]}=\sigma\left(Z^{[1]}\right) \\ Z^{[2]}=W^{[2]}
a^{[1]}+b^{[2]} \\ a^{[2]}=\sigma\left(Z^{[2]}\right) \\
\end{gathered}\] <b>Dimensions:</b> \(W^{[l]}=\left(n^{[l]},
n^{[l-1]}\right), a^{[l]}=\left(n^{[l]}, 1\right),
b^{[l]}\left(n^{[l]}, 1\right) \text { with } n^{[l]} \text { as
nodes in layer } l\)
