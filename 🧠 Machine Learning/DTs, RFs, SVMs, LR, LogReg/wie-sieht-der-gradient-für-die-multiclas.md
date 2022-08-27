## Note
nid: 1607452837897
model: Basic-d7a3e-4ce08
tags: ml::02_linear_classification
markdown: false

### Front
<p>Wie sieht der Gradient für die Multiclass Classification aus?
Vollziehen Sie die Berechnung nach.

### Back
<p>\[\begin{aligned} \frac{\partial
\operatorname{loss}_{i}}{\partial \boldsymbol{w}_{k}}
&=\frac{\partial}{\partial
\boldsymbol{w}_{k}}\left(\sum_{k=1}^{K} \boldsymbol{h}_{c_{i}, k}
\boldsymbol{w}_{k}^{T}
\boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)-\log
\left(\sum_{j=1}^{K} \exp \left(\boldsymbol{w}_{j}^{T}
\boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)\right)\right)
\\ &=\boldsymbol{h}_{c_{i}, k}
\boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)-\frac{\partial}{\partial
\boldsymbol{w}_{k}} \log \left(\sum_{j=1}^{K} \exp
\left(\boldsymbol{w}_{j}^{T}
\boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)\right) \\
&=\boldsymbol{h}_{c_{i}, k}
\boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)-\frac{1}{\sum_{j=1}^{K}
\exp \left(\boldsymbol{w}_{j}^{T}
\boldsymbol{\phi}\left(\boldsymbol{x}_{i}\right)\right)} \exp
\left(\boldsymbol{w}_{k}^{T}
\phi\left(\boldsymbol{x}_{i}\right)\right)
\phi\left(\boldsymbol{x}_{i}\right) \\
&=\underbrace{\phi\left(\boldsymbol{x}_{i}\right)}_{\text
{feature vector }} \underbrace{\left(\boldsymbol{h}_{c_{i},
k}-p\left(k \mid \boldsymbol{x}_{k}\right)\right)}_{\text
{"soft-max error" }} \end{aligned}\]
