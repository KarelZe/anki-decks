## Note
nid: 1653499610767
model: Basic-02d89
tags: 10_text_mining_bda
markdown: false

### Front
What do we <b>optimize</b> for in the <b>Skip-Gram model</b>?

### Back
<b>Softmax:</b>

Maximize the probability
\[\mathrm{p}\left(w_{O} \mid w_{I}\right)=\frac{\exp \left(v^{\prime}{ }_{w_{O}}{ }^{T} w_{I}\right)}{\sum_{w=1}^{W} \exp \left(v^{\prime}{ }_{w} v_{w_{I}}\right)}\]
where
\(v\) represents the output vector of our target word
\(v^{\prime}\) represents the output vector of our context word
\(W\) is the total vocabulary


Loss function can be defined as \(\frac{1}{T} \sum_{t=1}^{T} \sum_{-c \leq j \leq c, j \neq 0} \log p\left(w_{t+j} \mid w_{t}\right)\)
