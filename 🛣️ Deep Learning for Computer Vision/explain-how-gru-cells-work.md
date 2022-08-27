## Note
nid: 1655791345088
model: Basic-02d89-e0e22
tags: dl_cv::08_rnn
markdown: false

### Front
Explain how <b>GRU cells</b> work.

### Back
\(\left(\begin{array}{l}r_{t} \\ z_{t}\end{array}\right)=\left(\begin{array}{c}\text { sigm } \\ \text { sigm }\end{array}\right) W\left(\begin{array}{c}x_{t} \\ h_{t-1}\end{array}\right)\)

\(\tilde{h}_{t}=\tanh \left(W_{x h} x_{t}+W_{h h}\left(r_{t} * h_{t-1}\right)\right)\)
\(h_{t}=z_{t} * h_{t-1}+\left(1-z_{t}\right) * \tilde{h}_{t}\)

<b>Reset gate</b> \(r_{t}\) controls previous state \(h_{t-1}\).
<b>Output gate</b> \(z_{t}\) modulates new hidden state with old.

<b>Visualization:</b>
<img src="paste-f8e68932c1b85baf46f22cb2e71a37113d1e5f59.jpg">
