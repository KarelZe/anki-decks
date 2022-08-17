## Note
nid: 1629293018097
model: Basic-d7a3e
tags: 11_rnns, checklater
markdown: false

### Front
Explain what a GRU is.

### Back
<div><div>GRUs are a variant of RNNs using gates to control what information to remember and what to forget. A GRU is a <span style="font-weight: bold;">simpler variant</span> of the LSTM. It contains only an <span style="font-weight: bold;">update gate</span> \(z_t\) <span style="font-weight: bold;">(</span>fuse of the forget and input gate <span style="font-weight: bold;">or</span> fuse of long-term and working memory) <span style="font-weight: bold;">and reset gate </span>\(r_t\)<span style="font-weight: bold;"> </span>with different weights.</div></div><div>
</div><div>Equations given by:</div><div>
</div><div>\(\begin{aligned} r_{t} &=\sigma\left(W_{x r} x_{t}+W_{h r} h_{t-1}+b_{r}\right) \\ z_{t} &=\sigma\left(W_{x z} x_{t}+W_{h x} h_{t-1}+b_{z}\right) \\ \tilde{h}_{t} &=\tanh \left(W_{x h} x_{t}+W_{h h}\left(r_{t} \odot h_{t-1}\right)+b_{h}\right) \\ h_{t} &=z_{t} \odot h_{t-1}+\left(1-z_{t}\right) \odot \tilde{h}_{t} \end{aligned}\)
</div>
