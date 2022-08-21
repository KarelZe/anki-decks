## Note
nid: 1616230993203
model: Basic-b122e
tags: 10_Cluster_Modularity
markdown: false

### Front
Wie ist die gemeinsame Nachbarschaft zweier Knoten definiert?

### Back
\(\text { neighbourhood }\left(v_{i}, v_{j}\right)=\frac{\mid \text { neighbours }\left(v_{i}\right) \cap \text { neighbours }\left(v_{j}\right) \mid}{\mid \text { neighbours }\left(v_{i}\right) \cup \text { neighbours }\left(v_{j}\right) \mid}\)<div>
</div><div><b>Intution:</b></div><div>Ist eine Art Dichtemaß. Nahe 1 bedeutet, hohe Gemeinschaft. Nahe 0 kleine Gemeinschaft. </div><div>
</div><div>Im Zähler ist die Anzahl der gemeinsamen Nachbar-Knoten der Knoten \(v_i\) und \(v_j\). Im Nenner die Gesamtanzahl beider Knoten.</div>
