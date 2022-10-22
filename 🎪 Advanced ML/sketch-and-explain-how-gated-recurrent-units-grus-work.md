# Note
```
guid: q>g}CIu8Vh
notetype: Basic-d7a3e-4ce08
```

### Tags
```
12_lecture
```

## Front
Sketch and explain how Gated Recurrent Units (GRUs) work.

## Back
<div><img src="paste-05a2e6e75e31afa90981f25abe92174014a1d30f.jpg">
</div>
<div>LSTM networks do not only use an update gate \(\Gamma_{u}\) and its inverse \(1-\Gamma_{u}\), but three different gate types for modeling a similar, but even more popular behaviour. Besides of the update gate \(\Gamma_{u}\), which is again:

\[\Gamma_{u}=\operatorname{sigm}\left(W_{u}\left[a^{<t-1>}, x^{<t>}\right]+b_{u}\right)\]

there is also a so called forget gate \(\Gamma_{f}\) and a output gate \(\Gamma_{o}\) :

\[\begin{aligned}
\Gamma_{f} &=\operatorname{sigm}\left(W_{f}\left[a^{<t-1>}, x^{<t\rangle}\right]+b_{f}\right) \\
\Gamma_{o} &=\operatorname{sigm}\left(W_{o}\left[a^{<t-1>}, x^{<t>}\right]+b_{o}\right)
\end{aligned}\]

This gives a bonus in stability and makes LSTMs comparatively successful.
</div>
