# Note
```
guid: Km[TzWN,2H
notetype: Basic-d7a3e-4ce08
```

### Tags
```
ml::02_linear_classification
```

## Front
<p>Wie ist der <b>Data log-likelihood</b> für eine <b>Multiclass
Classification</b> definiert?

## Back
<p><b>Hintergrund:</b> Umformulierung conditional multinomial
distribution:
<p>\(\begin{aligned} p(c \mid \boldsymbol{x}) &=\prod_{k=1}^{K}
p(c=k \mid \boldsymbol{x})^{\boldsymbol{h}_{x, k}} \\
&=\prod_{k=1}^{K}\left(\frac{\exp \left(\boldsymbol{w}_{k}^{T}
\boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)}{\sum_{k^{\prime}=1}^{K}
\exp \left(\boldsymbol{w}_{k^{\prime}}^{T}
\boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)}\right)^{\boldsymbol{h}_{c,
k}} \end{aligned}\)
<p><b>Hintergrund 2:</b>
<p>\(p(c=i \mid \boldsymbol{x})=\frac{\exp
\left(\boldsymbol{w}_{i}^{T}
\phi(\boldsymbol{x})\right)}{\sum_{k=1}^{K} \exp
\left(\boldsymbol{w}_{k}^{T}
\boldsymbol{\phi}(\boldsymbol{x})\right)}\)
<p><b>Berechnung:</b>
<p>\(\begin{aligned} \log \operatorname{lik}\left(\mathcal{D},
\boldsymbol{w}_{1: K}\right) &=\sum_{i=1}^{N} \log p\left(c_{i}
\mid \boldsymbol{x}_{i}\right)=\sum_{i=1}^{N}
\underbrace{\sum_{k=1}^{K} \boldsymbol{h}_{c_{i}, k} \log p\left(k
\mid \boldsymbol{x}_{i}\right)}_{\operatorname{loss}_{i} \ldots
\text { loss of the ith sample }} \\ &=\sum_{i=1}^{N}
\sum_{k=1}^{K} \boldsymbol{h}_{c_{i},
k}\left[\boldsymbol{w}_{k}^{T}
\boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)-\log
\left(\sum_{j=1}^{K} \exp \left(\boldsymbol{w}_{j}^{T}
\boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)\right)\right]
\\ &=\sum_{i=1}^{N} \sum_{k=1}^{K} \boldsymbol{h}_{c_{i}, k}
\boldsymbol{w}_{k}^{T}
\boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)-\underbrace{\log
\left(\sum_{j=1}^{K} \exp \left(\boldsymbol{w}_{j}^{T}
\boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)\right)}_{\text
{independent from } \mathrm{k}} \underbrace{\sum_{k}
\boldsymbol{h}_{c_{i}, k}}_{=1} \end{aligned}\)
