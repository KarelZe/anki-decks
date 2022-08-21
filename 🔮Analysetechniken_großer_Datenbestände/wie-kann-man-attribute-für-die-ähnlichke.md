## Note
nid: 1609430835794
model: Basic-d7a3e
tags: 03_raeumliche_index_strukturen, checklater
markdown: false

### Front
<p>Wie kann man Attribute für die Ähnlichkeitssuche normalisieren?

### Back
<p>Haben Dimensionen unterschiedliche Einheiten, dann ist der
Abstand wenig aussagekräftig.
<p>Man normalisert mittels:
<p>\[a_{i}=\frac{v_{i}-\min v_{j}}{\max v_{j}-\min v_{j}},\]
<p>\(a_i \in \left[0,1\right]\)
<p>wobei \(v_{i}\) ein Wert aus dem betrachteten Tupel ist und
\(v_{j}\) ein Wert aus dem Wertebereich von \(v_{i}\) ist. Ich
stelle mir \(v\) als Matrix vor.
<p><b>Beispiel sklearn</b>:
<pre>X_std = (X - X.min(axis=0)) / (X.max(axis=0) - X.min(axis=0))</pre>
<pre>axis = 0 -> Spalten</pre>
