# Note
```
guid: ub`n**AVU&
notetype: Basic-d7a3e-4ce08
```

### Tags
```
12_lecture
```

## Front
Explain how <b>Gated Reccurent Units (GRUs)</b> tackle the <b>Vanishing Gradient Problem</b>.

## Back
The GRU's core is the so called Update Gate \(\Gamma_{u}\) :

\[\Gamma_{u}=\operatorname{sigm}\left(W_{u}\left[a^{<t-1>}, x^{<t>}\right]+b_{u}\right)\]

The sigmoid activation results in most of the cases in a value very close to \(\Gamma_{u} \approx 0\) or in a value \(\Gamma_{u} \approx 1\). In the context of the following Equation.

\[a^{<t>}=\Gamma_{u} \tilde{a}^{<t>}+\left(1-\Gamma_{u}\right) a^{<t-1>},\]

this means that the value of \(a^{<t>}\) is either mostly \(\tilde{a}^{<t>}\) or very similar to \(a^{<t-1>}\). Hence, when the Update Gate \(\Gamma_{u}\) is closed \(\left(\Gamma_{u} \approx 0\right)\), it is possible to propagate information \(a^{<t-1>}\) very far trough the network without loosing much of it. Now the gradients during the back-propagation won't vanish no more.
