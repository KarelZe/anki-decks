## Note
nid: 1611059431020
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1
markdown: false

### Front
<p>Was sind 3 <b>Eigenschaften </b>BIRCH-Ansatzes?</p>

### Back
<ul style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
  <li>Aufbau eines CF-Trees, der Datenverteilung beschreibt
  <li>CF-Tree ist sehr kompakt. Verbraucht daher wenig Platz und
  passt häufig in den Hauptspeicher.
  <li>Systematischer als partionsbasierte Verfahren.
  <li>I/O Kosten wachsen linear mit der Größe des Datenbestands,
  wenn CF-Tree in Hauptspeicher passt.
  <li>Clustering erhält man bereits nach einer Iteration. D. h.
  nach einem Scan über die DB.
  <li>Zusätzliche Schritte liefern aber besseres Clustering.
</ul>
