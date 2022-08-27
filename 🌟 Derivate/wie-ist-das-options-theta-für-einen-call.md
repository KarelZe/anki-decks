## Note
nid: 1618045538668
model: Basic-d7a3e-4ce08
tags: 06_risikomanagement, derivate::06_risikomanagement
markdown: false

### Front
Wie ist das Options-Theta für einen Call definiert? Wie für einen Put?

### Back
\(\Theta_{C}=\frac{\partial}{\partial t}
C=-\frac{\partial}{\partial T} C = -S N^{\prime}\left(d_{1}\right)
\frac{\sigma}{2 \sqrt{T-t}}-r X e^{-r(T-t)} N\left(d_{1}-\sigma
\sqrt{T-t}\right)\)
<div>
  \(\Theta_{P}=\frac{\partial}{\partial t} P=\Theta_{C}+r X
  e^{-r(T-t)}\)
</div>
