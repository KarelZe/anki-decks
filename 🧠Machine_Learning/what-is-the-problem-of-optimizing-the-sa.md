## Note
nid: 1659637825696
model: Basic-02d89
tags: 12_var_ae_ml
markdown: false

### Front
What is the problem of optimizing the sampling distribution \(q_{\phi}(z \mid x)\)  of variational autoencoders? How can it be resolved?

\[\mathcal{L}(q, p)=\frac{1}{N} \sum_{i} \int q_{\boldsymbol{\phi}}\left(\boldsymbol{z} \mid \boldsymbol{x}_{i}\right) \log p_{\boldsymbol{\varphi}}\left(\boldsymbol{x}_{i} \mid \boldsymbol{z}\right) d \boldsymbol{z}-\mathrm{KL}\left(q_{\boldsymbol{\phi}}\left(\boldsymbol{z} \mid \boldsymbol{x}_{i}\right) \| p_{\boldsymbol{\varphi}}(\boldsymbol{z})\right)\]

### Back
<ul><li>Different to standard max-likelihood: Here, samples are not fixed but generated!</li><li>Standard gradients can be used (related to policy gradients), but very inefficient as it does not use gradient information of \(\partial \log p_{\varphi}(x \mid z) / \partial \boldsymbol{z}\).</li></ul><b>Remedy:</b>
<ul><li>Reparametrization trick.
</li></ul>
