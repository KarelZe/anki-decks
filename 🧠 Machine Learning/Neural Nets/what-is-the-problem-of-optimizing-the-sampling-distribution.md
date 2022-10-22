# Note
```
guid: Agt<+zyym-
notetype: Basic-02d89-e0e22
```

### Tags
```
ml::12_var_ae
```

## Front
What is the problem of optimizing the sampling distribution \(q_{\phi}(z \mid x)\)  of variational autoencoders? How can it be resolved?

\[\mathcal{L}(q, p)=\frac{1}{N} \sum_{i} \int q_{\boldsymbol{\phi}}\left(\boldsymbol{z} \mid \boldsymbol{x}_{i}\right) \log p_{\boldsymbol{\varphi}}\left(\boldsymbol{x}_{i} \mid \boldsymbol{z}\right) d \boldsymbol{z}-\mathrm{KL}\left(q_{\boldsymbol{\phi}}\left(\boldsymbol{z} \mid \boldsymbol{x}_{i}\right) \| p_{\boldsymbol{\varphi}}(\boldsymbol{z})\right)\]

## Back
<ul>
  <li>Different to standard max-likelihood: Here, samples are not
  fixed but generated!
  <li>Standard gradients can be used (related to policy gradients),
  but very inefficient as it does not use gradient information of
  \(\partial \log p_{\varphi}(x \mid z) / \partial
  \boldsymbol{z}\).
</ul><b>Remedy:</b>
<ul>
  <li>Reparametrization trick.
</ul>
