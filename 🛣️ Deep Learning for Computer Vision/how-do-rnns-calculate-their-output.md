# Note
```
guid: jJd6[Wo,m_
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::08_rnn
```

## Front
How do RNNs calculate their output?

## Back
Get input at each time step \(\boldsymbol{x}_{t}\)
Learn a hidden state representation \(\boldsymbol{h}_{t}\)
\[
\begin{aligned}
h_{t} &=f_{W}\left(h_{t-1}, \mathcal{x}_{t}\right)\\
h_{t} &=\tanh \left(W_{h h} h_{t-1}+W_{x h} x_{t}\right) \\
y_{t} &=W_{h y} h_{t}
\end{aligned}
\]

With a single hidden vector \(\boldsymbol{h}\), output \(y\), is a function of the hidden state, \(W_{x h}\) input to hidden, \(W_{h h}\) hidden to hidden and \(W_{\text {hy }}\) hidden to output.

<b>Hint:</b>
Parameters are shared between every time step.

<b>Visualization:</b>
<img src="paste-6002175d8e54d99358150db92bc575e9a380e17b.jpg">
