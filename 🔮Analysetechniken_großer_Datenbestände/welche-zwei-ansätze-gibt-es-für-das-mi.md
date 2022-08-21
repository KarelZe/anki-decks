## Note
nid: 1608984946973
model: Basic-d7a3e
tags: 08_constrained_ar, checklater, ultra
markdown: false

### Front
<p><span>

Welche zwei Ansätze gibt es für das Mining von Association Rules unter Constraints?

</span>
</p>

### Back
<ul style="letter-spacing: normal; text-indent: 0px; 
 text-transform: none; white-space: normal; word-spacing: 0px;">
  <li style=""><b>Postprocessing</b><span style="font-weight:
  400;">: N</span>aive Lösung: Finde alle Frequent Itemsets mit
  Apriori und überprüfe dann für jede dieser Mengen, ob sie die
  Constraints erfüllen. D. h. man generiert alle Ergebnisse, im
  <b>Postprocessing-Schritt</b> werden dann Constraints angewendet.
  Hoher Aufwand! Kein Performancegewinn.
  <li style="font-weight: 400;"><strong>Optimierung</strong>:
  Umfassende Analyse der Eigenschaften von Constraints. Ziel ist es
  Constraints möglichst tief im Algorithmus zu verankern.
</ul>
