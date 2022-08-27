## Note
nid: 1609155706028
model: Basic-d7a3e-4ce08
tags: ml::06_em_for_dim_reduction
markdown: false

### Front
<p><span>Was ist die Grundidee von <strong>Mixture
Models</strong>?</span>

### Back
<div style="line-height: 19px;">
  <span style="white-space: pre;">Erzeuge eine komplexe Verteilung,
  indem man einfache verbindet z. B. Normal-Verteilungen.</span>
</div>
<div style="line-height: 19px;"></div>
<div style="line-height: 19px;">
  <span style="white-space: pre;"><b>Beispiel:</b></span>
</div>
<div style="line-height: 19px;"><img src="1WVxqxhuSnvQ5eHTUVzd.png"
style="width: 318px;"></div>
<div style="line-height: 19px;"></div>
<div style="line-height: 19px;"></div>
<div style="line-height: 19px;">
  \(p(\boldsymbol{x})=\sum_{k=1}^{K} p(k) p(\boldsymbol{x} \mid
  k),\)
</div>
<div style="line-height: 19px;"></div>
<div style="line-height: 19px;">
  wher \(p(k)\) is the mixture coefficient, \(K\) is the number of
  components and \(p(\boldsymbol{x} \mid k)\) is the \(k\)-th
  mixture component.
</div>
