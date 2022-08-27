## Note
nid: 1628323506525
model: Basic-d7a3e-4ce08
tags: 02_uebung, 02_uebung_rs
markdown: false

### Front
Geben Sie die <b>Formel</b> an, wie sich die
<b>Funktionswahrscheinlichkeit</b> für Systeme mit
<b>Mehrheitsentscheider</b> berechnen lässt.

### Back
\[\varphi_{m}^{n}=\varphi(\mathrm{V}) *
\sum_{k=n}^{m}\left(\begin{array}{l} m \\ k \end{array}\right) *
\varphi(K)^{k} *(1-\varphi(K))^{(m-k)},\]
<div>
  wobei \(\varphi(K):\) Funktionswahrscheinlichkeit der Komponenten
  und
</div>
<div>
  \(\varphi(V):\) Funktionswahrscheinlichkeit des Entscheiders
  (Voter) ist.
</div>
<div>
  Entscheider ist <b>single point of failure</b>. Am besten sollte
  \(\varphi(V)=1\) sein.
</div>
