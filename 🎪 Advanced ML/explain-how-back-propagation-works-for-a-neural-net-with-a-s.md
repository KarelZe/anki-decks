# Note
```
guid: b9CzI)Wr|J
notetype: Basic-d7a3e-4ce08
```

### Tags
```
adv_ml::10_lecture
```

## Front
Explain how <b>back-propagation</b> works for a <b>neural net with
a single target and many inputs</b>.
<div><img src="paste-fc40018ee05ea404971281b1c8d2f0edfedaa9bc.jpg"></div>

## Back
<div>
  The cost objective Function between actual output \(y\) and
  predicted output \(\hat{y}\).
</div>\[\begin{aligned} \min _{w, v}
&=\mathbf{E}\left[(y-\hat{y})^{2}\right] \\
&=\varepsilon(w, v) \\ \Delta w=&-\eta \mathbb{E}
\nabla_{w}\left[(y-\hat{y})^{2}\right] \\ =&-\eta \nabla_{w}
\varepsilon(w) \end{aligned}\]
<div>
  Introduce a momentum term for iterative minimization of the cost
  function:
</div>
<div>
  \[\Delta w(t)=\alpha \Delta w(t-1)-\eta \frac{\partial
  \varepsilon(w(t)}{\partial w}\]
</div>
