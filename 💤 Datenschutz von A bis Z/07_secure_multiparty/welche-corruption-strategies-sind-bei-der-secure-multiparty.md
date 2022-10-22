# Note
```
guid: E,*4s%pOnZ
notetype: Basic-9c783
```

### Tags
```
angreifer
datenschutz::07_secure_multiparty
ultra
```

## Front
Welche <b>Corruption Strategies</b> sind bei der <b>Secure
Multiparty Computation</b> möglich? (Angreifermodelle)

## Back
Knoten \(P_0, \ldots P_n\) können sich verhalten:
<ul>
  <li>Malicious
  <li>Covered
  <li>Honest-but-curious
</ul><b>Corruption Strategy</b>
<ul>
  <li><b>Static:</b> Angreifer entscheidet vor Protokollstart,
  welche Knoten \(\left\{\mathrm{P}_{\mathrm{i}}, \ldots
  \mathrm{P}_{\mathrm{j}}\right\} \subseteq\left\{\mathrm{P}_0,
  \ldots \mathrm{P}_{\mathrm{n}}\right\}\) übernommen werden und
  sich malicious, covered, honest-but-curious verhalten
  <li><b>Dynamic:</b> Angreifer kann während der
  Protokoll-Ausführung Knoten korrumpieren
  <li><b>Proactive:</b> Knoten können während Ausführung "ehrlich"
  werden
</ul>
