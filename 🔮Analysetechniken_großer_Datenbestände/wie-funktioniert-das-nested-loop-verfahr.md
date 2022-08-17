## Note
nid: 1612865348151
model: Basic-d7a3e
tags: 10_id_von_outliern, checklater
markdown: false

### Front
Wie funktioniert das <em>nested-loop</em> Verfahren zur <b>Ausreiser-Ermittlung</b>?

### Back
<b>Beispiel:</b><div>
</div><img src="65307264.png"><div>
</div><div>Man teilt Datenbestand in zwei Relationen. Hierfür nimmt man ein Tupel aus der äußeren Relation und geht über die linke Relation. Dies wiederholt man für alle Tupel.</div><div><img src="61792964.png">
</div><div>
</div><div>Man zählt dann für jeden Tupel der äußeren Relation die Zahl der Vorkommen und beendet dann sobald ein Abbruchkriterium erreicht wird.</div><div>
</div><div><b>Anwendung auf Outlier-Erkennung (nach Knorr):</b></div><div>Man bestimmt naiv die K-NNs mit einem sequentiellen Scan über die Datenbank.</div><div>
</div><div>Hierfür teilt man den Datenbestand in zwei Teile auf und geht über jedes Tupel \(t_i\) im ersten Array drüber und zählt wie oft gilt \(\operatorname{dist}(t_i, t_j) \leq D\). Die Distanz wird zu jedem \(t_j\) im ersten Teildatenbestand bestimmt. Man inkrementiert bei Treffer einen Zähler. Gilt dass die Anzahl \(> M\) ist. \(M\) ist die absolute Anzahl an Datenpunkten, die überschritten werden muss, damit es sich um keinen Outlier handelt.</div><div>
</div><div>Man bestückt einen zweiten Array. Man vergleicht dann jedes unmarkierte Tupel \(t_i\) des ersten Arrays gegen jedes Tupel \(t_j\) im zweiten Array, erhöht ggf. Zähler und markiert das Objekt ggf. als Nicht-Ausreißer. Dann vertauschen der Partitionen.</div><div>
</div><div><b>Tonspur Vorlesung:</b></div><div>Selfjoin mit 2 Kopien des Datenbestands. Man geht Objekte der Reihe nach durch in linker Relation und geht dafür über die Elemente der rechten Relation und prüft, ob das Objekt innerhalb der Kugel mit Radius \(D\) erhöht und erhöht einen Zähler. Ist man einmal über komplette rechte Relation gelaufen, dann kennt man für das Objekt in linker Relation, die Anzahl der Objekte, die in Nachbarschaft liegen. Liegt die Anzahl der Objekte oberhalb von \(p\) (gemeint ist \(m\)), dann ist Objekt kein Outlier, ist sie kleiner oder gleich dann handelt es sich um Outlier und Objekt wird ausgegeben. man würde es blockweise implementieren. Man kann auch Beobachtung / Schleifendurchlauf abbrechen, wenn man z. B. genügend Objekte findet.
</div>
