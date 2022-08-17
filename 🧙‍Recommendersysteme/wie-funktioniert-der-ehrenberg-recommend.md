## Note
nid: 1592759372158
model: Basic-b122e
tags: 08_Ehrenberg
markdown: false

### Front
Wie funktioniert der Ehrenberg-Recommender? Das heißt welche Schritte umfasst er?

### Back
<ol>
<li><p>Berechne (zähle) für alle Informationsprodukte <span class="math inline">\(x\)</span> in Warenkörben die Häufigkeitsverteilung für <span class="math inline">\(r\)</span> Käufe <span class="math inline">\((x, i)\)</span></p></li>
<li><p>Alle Häufigkeitsverteilungen mit weniger als <span class="math inline">\(l\)</span> Beobachtungen werden nicht weiterverarbeitet</p></li>
<li><p>Für jede Häufigkeitsverteilung:</p>
<ol>
<li><p>Berechne einen robusten Mittelwert (ohne das <span class="math inline">\(t(2.5)\)</span> Perzentil der Paare mit hohen Kaufraten)</p></li>
<li><p>Schätze den Parameter <span class="math inline">\(q\)</span> der LSD-Verteilung (Bisektion/Newton)</p></li>
<li><p>Passt das Modell? Verwenden <span class="math inline">\(\chi^{2}\)</span> -Test mit <span class="math inline">\(\alpha=0.01\)</span> zwischen:</p>
<ol>
<li><p>Beobachteten Käufen</p></li>
<li><p>Erwarteten Käufen (Auf Basis des LSD-Modells erwarteten Käufen mit geeigneter Partitionierung)</p></li>
</ol></li>
<li><p>Bestimme die Ausreißer (konservativ: Ausreißer bei <span class="math inline">\(r\)</span> liegen über <span class="math inline">\(\sum_{r}^{\infty} p_{r}\)</span>)</p></li>
<li><p>Falls signifikantes LSD-Modell mit Ausreißern gegeben: Liste der Ausreißer als "Empfehlungsliste"</p></li>
</ol></li>
</ol>
