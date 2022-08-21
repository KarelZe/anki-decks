## Note
nid: 1610960004319
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1, checklater
markdown: false

### Front
<p>Wie funktioniert das Verfahren <b>DIANA</b> bei <b>divisivem
hierarchischem Clustering</b>?

### Back
<p>Auswahl des Clusters \(C\) mit dem größten Durchmesser. Suche nach dem abseitigsten Datenobjekt \(o\) in \(C\). (höchster durchschnittlicher Abstand von den anderen Objekten. Dieses Objekt ist Seed für die sg. SplinterGroup:={o} ("Splittergruppe").</p><p>Danach wiederholtes Einfügen des \(o' \in C \backslash\) SplinterGroup mit dem größten \(D\left(o'\right)>0\) in SplinterGroup, bis für alle o' \(\in \mathrm{C} \backslash\) SplinterGroup gilt: \(\mathrm{D}\left(o^{\prime}\right) \leq 0\):</p><p>\(D\left(o'\right)=\sum_{o_{j} \in C \backslash \text { SplinterGroup }} \frac{d\left(o^{\prime}, o_{j}\right)}{\mid C \backslash \text { SplinterGroup } \mid}-\sum_{o_{i} \in \text { SplinterGroup }} \frac{d\left(o^{\prime}, o_{i}\right)}{\mid \text { SplinterGroup } \mid}\)</p><p>Zweiter Summand: Durchschnittlicher Abstand zur SplinterGroup.</p><p>Erster Summand: dto. Durchschnittlicher Abstand zur Nicht-SplinterGroup/rest.</p><p>Wenn \(D\left(o'\right) \leq 0\), gehört \(o'\) eher zum Rest als zur SplinterGroup. Konzept ähnlich zu Sillhouettekoeffizient eines Objekts.</p><p><b>Intuition</b></p><p><span>

</span></p><p>Das abseitigste Objekt \(o\) wird auf jeden Fall abgespalten, dann muss man noch schauen, welche Objekte noch mit abgespalten werden. \(o\) ist Nukleus der SplinterGroup. Man berechnet Abstand zwischen Objekt \(o'\) und SplinterGroup. </p><p>Ist Abstand zu Objekten der SplinterGroup klein (nach Minus), bedeutet das dass Objekt \(o'\) zu Splittergruppe gehört. Alles vor minus ist Rest. Weiterhin berechnet man Abstand zu restlichen Objekten d. h. Nicht-Splittergruppe.</p><p>Dann betrachtet man Differenz zwischen Distanzen.</p><p>Durch Einfügen von \(o'\) in SplinterGroup muss \(d\) nochmal für alle anderen Datenobjekte berechnet werden, weil Distanz zu SplinterGroup / dem Rest sich ggf. verändert hat.</p><p></p>
