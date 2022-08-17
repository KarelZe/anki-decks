## Note
nid: 1614964992718
model: Basic-b122e
tags: 01_uebung_rs, 01_vorlesung, 02_rechnerarchitektur, checklater
markdown: false

### Front
Woraus setzt sich die <b>Leistungsaufnahme</b> zusammen?

### Back
<p>\(P_{\text {total }}=P_{\text {switching }}+P_{\text
{shortcirciut }}+P_{\text {static }}+P_{\text {leakage }}\)
<p>Leistungsverbrauch bei Zustandsänderung
<ul>
  <li>\(\mathbf{P}_{\text {switching }}\): Laden oder Schalten
  einer kapazitiven Last
  <li>\(\mathrm{P}_{\text {shortcircuit }}\) Leistungsverbrauch
  während des Übergangs am Ausgang in einem CMOS Gatter, wenn sich
  die Eingänge ändern
</ul>
<p>Statischer Leistungsverbrauch (unabhängig von
Zustandsänderungen)
<ul>
  <li>\(\mathrm{P}_{\text {static }}\): Statischer
  Leistungsverbrauch
  <li>\(\mathbf{P}_{\text {leakage }}\): Leistungsverbrauch durch
  Kriechströme
</ul>
<p>\(P_{\text {switching }}=C_{\text {eff }} \times V_{\text {dd }}
2 \times f\), mit:
<ul>
  <li>\(\mathrm{C}_{\text {eff }}\): effektive Kapazität:
  \(\mathrm{C} \times a\)
  <li>\(\mathrm{V}_{\mathrm{dd}}=\mathrm{V}_{\mathrm{swing}}\)
</ul>
<p>\(\mathrm{P}_{\text {shortcircuit }}=I_{\text {mean }} \times
\mathbf{V}_{\mathrm{dd}},\) mit
<ul>
  <li>\(\mathrm{I}_{\text{mean }}\): mittlerer Strom während des
  Wechsels des Eingangssignals
  <li>Kann für ein Gatter mit kurzen Eingangsflanken minimiert
  werden, auf Kosten von langen Übergangszeiten am Ausgang
  <li>Für eine Menge von Gatter wird versucht, gleiche Zeiten für
  steigende und fallende Flanken am Eingang und am Ausgang zu
  erhalten
</ul>
<p>\(\mathrm{P}_{\text {leakage }}\): Bei realen CMOS-Schaltungen
kommt zu dem Stromfluss beim Wechsel des logischen Pegels ein
weiterer ständiger Stromfluss hinzu: Leckströme Leakage
<ul>
  <li>Leckströme entstehen, da die Widerstände zwischen den
  Leiterbahnen der integrierten Schaltkreise nicht unendlich hoch
  sind.
  <li>Leckströme wachsen mit zunehmender Integrationsdichte
  <li>bei Integrationsdichten mit Strukturen kleiner als 100 nm
  kann die Leistungsaufnahme aufgrund von Leckströmen nicht mehr
  vernachlässigt werden.
</ul>
