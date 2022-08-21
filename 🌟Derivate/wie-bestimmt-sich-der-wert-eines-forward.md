## Note
nid: 1635148929849
model: Basic-d7a3e
tags: 02_forwards_futures, checklater
markdown: false

### Front
Wie bestimmt sich der Wert eines <b>Forwards </b>in \(t=0\)? Wie in \(t \leq T\)?

### Back
Wert in \(t=0\):
<div>
  \(f(0,T)= K\) (vereinbarter fairer Terminpreis)
</div>
<div>
  \(W^K(0,T) = 0\) (Wert des Forwards bei Abschluss)
</div>
<div>
  Forward soll für beide Parteien fair sein!
</div>
<div>
  Wert in Zeitpunkt \(t \leq T\):
</div>
<div>
  Allgemein ist \(f(t,T) \neq K\), weil Markt nach oben oder unten
  geht.
</div>
<div>
  Falls \(f(t,T) > K\), dann ist \(W^K(t,T) > 0\), ansosten
  ist \(W^K(t,T) < 0\).
</div>
<div>
  Der Wert des Futures bestimmt sich dann als:
</div>
<div>
  <div>
    \(W^{K}(t, T)=\frac{f(t,T)-K}{(1+r)^{T- t}}\)
  </div>
</div>
