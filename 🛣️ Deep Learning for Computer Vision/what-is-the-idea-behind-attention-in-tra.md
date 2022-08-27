## Note
nid: 1656321253380
model: Basic-02d89-e0e22
tags: dl_cv::misc
markdown: false

### Front
What is the <b>idea</b> behind <b>attention in translation</b>?

### Back
While generating the new word, "attend" to relevant source word.
Next word depends upon previous words and some context vector.
<b>Context vector:</b> \(p(y)=\prod_{t=1}^{T 2} p\left(y_{t}
\mid\left\{y_{1}, \ldots, y_{t-1}\right\}, c\right)\) <b>Attention
context vector</b> \[c_{t}=\sum_{j=1}^{T 1} \alpha_{t j} h_{j}\] A
weighted combination of source encodings such that \(\sum_{j}
\alpha_{j}=1.\) <img src= 
"paste-26cc043b4bec095d3755b96aa836f21158046fc0.jpg">
