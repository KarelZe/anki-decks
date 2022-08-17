## Note
nid: 1612262654523
model: Basic-d7a3e
tags: 09_bayesian_learning, ultra
markdown: false

### Front
Welche beiden Schritte sind notwendig bei <b>Bayesian Linear
Regression</b>?

### Back
<b>compute posterior:</b>
<div>
\[p(\boldsymbol{w} \mid \boldsymbol{X}, \boldsymbol{y})=\frac{p(\boldsymbol{y} \mid \boldsymbol{X}, \boldsymbol{w}) p(\boldsymbol{w})}{p(\boldsymbol{y} \mid \boldsymbol{X})}=\frac{p(\boldsymbol{y} \mid \boldsymbol{X}, \boldsymbol{w}) p(\boldsymbol{w})}{\int p(\boldsymbol{y} \mid \boldsymbol{X}, \boldsymbol{w}) p(\boldsymbol{w}) d \boldsymbol{w}}\]

</div><div><b>compute predictive distribution:</b> </div><div>
</div><div>Integrate posterior out:</div><div>
</div>\[p\left(y^{*} \mid \boldsymbol{x}^{*}, \boldsymbol{X}, \boldsymbol{y}\right)=\int p\left(y^{*} \mid \boldsymbol{w}, \boldsymbol{x}^{*}\right) p(\boldsymbol{w} \mid \boldsymbol{X}, \boldsymbol{y}) d \boldsymbol{w},\]
<div>
</div><div>where \(p(\boldsymbol{w} \mid \boldsymbol{X}, \boldsymbol{y})\) is the posterior and \(p\left(y^{*} \mid \boldsymbol{w}, \boldsymbol{x}^{*}\right)\) is the parameter-specific prediction.</div><div>
</div>
