## Note
nid: 1606548236709
model: Basic-d7a3e
tags: 03_model_selection, checklater
markdown: false

### Front
<p>Wie funktioniert das <b>Hinzufügen von Rauschen</b> für
<b>linear regression model</b>?

### Back
<p>Man fügt Rauschen (noise) hinzu, um wenig robuste Lösungen herauszufiltern.</p><p><img src="1SLbEBB1nftnQiWXph7u.png" style="width: 366px;">
</p><p>Für ein LR model Rauschen ist gegeben durch:</p><p>\(f(\boldsymbol{x}+\boldsymbol{\epsilon})=\boldsymbol{w}^{T}(\boldsymbol{x}+\boldsymbol{\epsilon}), \quad \boldsymbol{\epsilon} \sim \mathcal{N}(\mathbf{0}, \lambda \boldsymbol{I})\)
</p><p>Damit ergibt sich für den MSE:</p><p>\(\begin{aligned}
\operatorname{MSE}(\boldsymbol{w}) &=\mathbb{E}_{\boldsymbol{x}, y, \boldsymbol{\epsilon}}\left[\left(\boldsymbol{w}^{T} \boldsymbol{x}-y+\boldsymbol{w}^{T} \boldsymbol{\epsilon}\right)^{2}\right] \\
&=\underbrace{\mathbb{E}_{\boldsymbol{x}, y}\left[\left(\boldsymbol{w}^{T} \boldsymbol{x}-y\right)^{2}\right]}_{n \mathbf{S S E}(\boldsymbol{w})}+2 \underbrace{\mathbb{E}_{\boldsymbol{x}, y, \epsilon}\left[\left(\boldsymbol{w}^{T} \boldsymbol{x}-y\right) \boldsymbol{w}^{T} \boldsymbol{\epsilon}\right]}_{=0, \text { zero mean, i.i.d. noise }}+\underbrace{\mathbb{E}_{\boldsymbol{x}, y}\left[\left(\boldsymbol{w}^{T} \boldsymbol{\epsilon}\right)^{2}\right]}_{\lambda \boldsymbol{w}^{T} \boldsymbol{w}} \\
&=n \operatorname{SSE}(\boldsymbol{w})+\lambda\|\boldsymbol{w}\|_{2}^{2}
\end{aligned}\)
</p><p>Das Hinzufügen von Rauschen entspricht also einer Regularisierung mit \(\ell_2\) <b>Norm</b>. Mittlere Term streicht sich, da \(\epsilon\) mit nichts anderem korreliert ist. </p>
