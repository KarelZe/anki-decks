# Note
```
guid: A6:W2cFT@k
notetype: Basic-02d89-e0e22
```

### Tags
```
ml::12_var_ae
```

## Front
What does \(q(\boldsymbol{z})\) approximate in a variational distribution?

## Back
\[\begin{aligned}
\mathrm{KL}(q(\boldsymbol{z}) \| p(\boldsymbol{z} \mid x))=& \int q(\boldsymbol{z}) \log \frac{q(\boldsymbol{z})}{p(\boldsymbol{z} \mid x)} d \boldsymbol{z}=\int q(\boldsymbol{z}) \log \frac{p(x) q(\boldsymbol{z})}{p(\boldsymbol{x} \mid z) p(\boldsymbol{z})} d \boldsymbol{z}=\int q(\boldsymbol{z}) \log \frac{q(\boldsymbol{z})}{p(\boldsymbol{x} \mid z) p(\boldsymbol{z})} d \boldsymbol{z}+\text { const } \\
=&-\mathcal{L}(q, p)+\text { const } \\
& \Rightarrow \operatorname{argmin}_{q} \mathrm{KL}(q(\boldsymbol{z}) \| p(\boldsymbol{z} \mid x))=\operatorname{argmax}_{q} \mathcal{L}(q, p)
\end{aligned}\]

By maximizing the variational lower bound w.r.t \(q(\boldsymbol{z})\), the variational distribution will approximate the posterior, i.e.,
\[q(\boldsymbol{z}) \approx p(\boldsymbol{z} \mid \boldsymbol{x})\]
