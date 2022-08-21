## Note
nid: 1629478386396
model: Basic-d7a3e
tags: 00_klausurfragen, ultra
markdown: false

### Front
Write down the objective of linear binary logistic regression. The samples are given by \(x_{i}\) and the labels by \(c_{i} \in\{0,1\}\). How is \(p\left(c_{i} \mid \boldsymbol{x}_{i}\right)\) assumed to be distributed in binary logistic regression?

### Back
\[
\operatorname{argmax}_{\boldsymbol{w}} \sum_{i=1}^{N} c_{i} \log \left(\sigma\left(\boldsymbol{w}^{T} \boldsymbol{x}_{i}\right)\right)+\left(1-c_{i}\right) \log \left(1-\sigma\left(\boldsymbol{w}^{T} \boldsymbol{x}_{i}\right)\right)
\]
Logistic regression assumes \(p\left(c_{i} \mid x_{i}\right)\) to be Bernoulli distributed
