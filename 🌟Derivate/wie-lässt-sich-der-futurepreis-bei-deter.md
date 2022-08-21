## Note
nid: 1635751903430
model: Basic-d7a3e
tags: 02_forwards_futures, checklater
markdown: false

### Front
Wie lässt sich der <b>Futurepreis</b> bei <b>deterministischen
Zinssätzen</b> herleiten?

### Back
Es gilt \(r\) ist ein risikoloser Periodenzins \(F(t,n) = F^t\)
bezeichnet ein Future, \(f(t,n) = f^t\) ein Forward.
<div>
  <div><img src=
  "paste-ff3beed991d28b2b6b577f39c64f9d5577cb7535.jpg"></div>
</div>
<div>
  Zunächst kauft man \(e^r\) Futures. Kauf löst keinen
  Zahlungsstrom aus. An Tag findet dann erstmaliges
  <b>making-to-market</b> statt. Je nachdem muss man Mittel anlegen
  oder aufnehmen. Gleichzeitig geht man in \(e^2r\) Futures long.
  Für diese und die aus \(t = 0\) findet wieder in \(t = 2\) ein
  making-to-market statt.
</div>
<div>
  Das Ergebnis ergibt sich dann als Summe in \(n\). Die
  Summenspalte ermittelt sich aus:
</div>
<div>
  \(\left(F^{1}-F^{0}\right) e^{n r} = \left(F^{1}-F^{0}\right)
  e^{r} e^{n-1}\)
</div>
<div>
  oder
</div>
<div>
  \(\left(F^{2}-F^{1}\right) e^{n r} = \left(F^{2}-F^{1}\right)
  e^{r} e^{n-2}\). Für \(n-2\) siehe Anzahl der Einträge in Spalte
  \(t=2\).
</div>
<div>
  Das Ergebnis der Strategie in Futures zum Zeitpunkt \(n\),
  welches ohne Kapitaleinsatz erreicht wird, ist:
</div>
<div>
  \(\left(F^{n}-F^{0}\right) e^{n r}=\left(S(n)-F^{0}\right) e^{n
  r}\).
</div>
