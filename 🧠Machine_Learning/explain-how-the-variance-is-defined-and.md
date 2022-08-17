## Note
nid: 1629455751318
model: Basic-d7a3e
tags: 03_model_selection, checklater
markdown: false

### Front
Explain how the <b>Variance</b> is defined and what it is?

### Back
<div><div>\[\mathbb{E}_{D_{n}}\left[\mathbb{E}_{x, y}\left[\left(\hat{f}_{D_{n}}(\boldsymbol{x})-\hat{f}_{*}(\boldsymbol{x})\right)^{2}\right]\right],\]
</div><div>
</div><div>where \(\hat{f}_{*}(\boldsymbol{x})\) is \(\mathbb{E}_{D_{n}}\left[\hat{f}_{D_{n}}(\boldsymbol{x})\right]\) is the average estimate, averaged over all data sets of size \(n\) and \(\hat{f}_{D_{n}}\) is the estimate of \(f\) we obtain using data \(D_n\). We do the comparsion with the optimal function one could get \(\hat{f}_{*}(\boldsymbol{x})\), not the real function.</div></div><div><ul><li>Difference of the estimates to the "best" estimates</li><li>Due to limited size of the data set</li><li>Depends on the the number of data points</li></ul></div>
