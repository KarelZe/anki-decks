## Note
nid: 1607857351769
model: Basic-d7a3e-4ce08
tags: checklater, ml::05_dim_reduction, ultra
markdown: false

### Front
<p>Wie funktioniert die Minimierung des Fehlers bei der
<b>Zerlegung</b> <i>(decomposition)</i>?

### Back
<p>Assuming a single basis vector the error can be written as:
<p>\(\begin{aligned} E\left(\boldsymbol{u}_{1}\right)
&=\sum_{i=1}^{N}\left\|\boldsymbol{x}_{i}-\tilde{\boldsymbol{x}}_{i}\right\|^{2}=\sum_{i=1}^{N}\|\boldsymbol{x}_{i}-\underbrace{\left(\boldsymbol{u}_{1}^{T}
\boldsymbol{x}_{i}\right)}_{z_{i 1}} \boldsymbol{u}_{1}\|^{2} \\
&=\sum_{i=1}^{N} \boldsymbol{x}_{i}^{T}
\boldsymbol{x}_{i}-2\left(\boldsymbol{u}_{1}^{T}
\boldsymbol{x}_{i}\right)^{2}+\left(\boldsymbol{u}_{1}^{T}
\boldsymbol{x}_{i}\right)^{2} \boldsymbol{u}_{1}^{T}
\boldsymbol{u}_{1}=\sum_{i=1}^{N} \boldsymbol{x}_{i}^{T}
\boldsymbol{x}_{i}-\left(\boldsymbol{u}_{1}^{T}
\boldsymbol{x}_{i}\right)^{2} \\ &=\sum_{i=1}^{N}
\boldsymbol{x}_{i}^{T} \boldsymbol{x}_{i}-z_{i 1}^{2}
\end{aligned}\)
<p>\(\Rightarrow \underset{\boldsymbol{u}_{1}}{\arg \min }
E\left(\boldsymbol{u}_{1}\right)=\underset{\boldsymbol{u}_{1}}{\arg
\max } \sum_{i=1}^{N} z_{i
1}^{2}=\underset{\boldsymbol{u}_{1}}{\arg \max }
\sum_{i=1}^{N}\left(\boldsymbol{u}_{1}^{T}
\boldsymbol{x}_{i}\right)^{2}\)
<p>Note that:\(z_{i1}=\boldsymbol{u}_{1}^{T} \boldsymbol{x}_{i}\).
Minimizing the error is equivalent to maximizing the variance in
projection (Assuming a zero mean on the data). A zero mean
projection can be assured by subtracting the mean from the data
<p>
\(\overline{\boldsymbol{x}}_{i}=\boldsymbol{x}_{i}-\boldsymbol{\mu}\)
