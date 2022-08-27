## Note
nid: 1614964992718
model: Basic-d7a3e-4ce08
tags: 01_vorlesung, checklater, rs::01_uebung, rs::02_rechnerarchitektur
markdown: false

### Front
Woraus setzt sich die <b>Leistungsaufnahme</b> zusammen?

### Back
<p>\(P_{\text {total }}=P_{\text {switching }}+P_{\text {shortcirciut }}+P_{\text {static }}+P_{\text {leakage }}\)</p>
<p>Leistungsverbrauch bei Zustandsänderung</p>
<ul>
<li>\(\mathbf{P}_{\text {switching }}\): Laden oder Schalten einer kapazitiven Last</li>
<li>\(\mathrm{P}_{\text {shortcircuit }}\) Leistungsverbrauch während des Übergangs am Ausgang in einem CMOS Gatter,
        wenn sich die Eingänge ändern</li>
</ul>
<p>Statischer Leistungsverbrauch (unabhängig von Zustandsänderungen)</p>
<ul>
<li>\(\mathrm{P}_{\text {static }}\): Statischer Leistungsverbrauch</li>
<li>\(\mathbf{P}_{\text {leakage }}\): Leistungsverbrauch durch Kriechströme</li>
</ul>
<p>\(P_{\text {switching }}=C_{\text {eff }} \times V_{\text {dd }} 2 \times f\), mit:</p>
<ul>
<li>\(\mathrm{C}_{\text {eff }}\): effektive Kapazität: \(\mathrm{C} \times a\)</li>
<li>\(\mathrm{V}_{\mathrm{dd}}=\mathrm{V}_{\mathrm{swing}}\)</li>
</ul>
<p>\(\mathrm{P}_{\text {shortcircuit }}=I_{\text {mean }} \times \mathbf{V}_{\mathrm{dd}},\) mit</p>
<ul>
<li>\(\mathrm{I}_{\text{mean }}\): mittlerer Strom während des Wechsels des Eingangssignals</li>
<li>Kann für ein Gatter mit kurzen Eingangsflanken minimiert werden, auf Kosten von langen Übergangszeiten am Ausgang</li>
<li>Für eine Menge von Gatter wird versucht, gleiche Zeiten für steigende und fallende Flanken am Eingang und am Ausgang zu erhalten</li>
</ul>
<p>\(\mathrm{P}_{\text {leakage }}\): Bei realen CMOS-Schaltungen kommt zu dem Stromfluss beim Wechsel des logischen Pegels ein weiterer ständiger Stromfluss hinzu: Leckströme Leakage</p>
<ul>
<li>Leckströme entstehen, da die Widerstände zwischen den Leiterbahnen der integrierten Schaltkreise nicht unendlich hoch sind.</li>
<li>Leckströme wachsen mit zunehmender Integrationsdichte</li>
<li>bei Integrationsdichten mit Strukturen kleiner als 100 nm kann die Leistungsaufnahme aufgrund von Leckströmen
        nicht mehr vernachlässigt werden.</li>
</ul>
