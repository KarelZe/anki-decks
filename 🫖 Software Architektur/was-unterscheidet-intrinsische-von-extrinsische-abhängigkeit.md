# Note
```
guid: LvI[a-lRS-
notetype: Basic-d7a3e-4ce08
```

### Tags
```
05_modelling_quality
performance
```

## Front
Was unterscheidet <b>intrinsische</b> von <b>extrinsische
Abhängigkeiten</b> zwischen Qualitäts-Attributen? Nennen Sie
jeweils ein Beispiel.

## Back
<p><strong>Intrinsisch:</strong> Die Definition der Eigenschaft A
involviert die Eigenschaft B. D. h. per Definition zwei
Qualitätsattribute zusammenhängen.
<ul>
  <li><strong>Beispiel:</strong> <em>Das System wird als
  <b>verfügbar</b> bezeichnet, wenn die Antwortzeit unter <b>5
  ms</b> liegt. Man definiert Verfügbarkeit über Reaktionszeit
  (~Zeit bis Feedback an Nutzer erfolgt).</em>
</ul>
<p><strong>Extrinsisch:</strong> Veränderungen der Eigenschaft A
beeinflussen Eigenschaft B in einer Architektur C. <em>D. h.
Architektur beeinflusst, ob zwei Qualitätseigenschaften in
Abhängigkeit stehen.</em>
<ul>
  <li><strong>Beispiel:</strong> <em>Etwa verbessern grob granulare
  Komponenten die Performanz, verschlechtern aber die
  Wartbarkeit.</em>
  <li><b>Beispiel:</b> <em>Man repliziert Server. Zwar erhöht
  Replikation von Servern die Performanz, es bleibt aber unklar, ob
  Verfügbarkeit verbessert wird, sofern weitere Bottlenecks
  bestehen.</em>
</ul>
