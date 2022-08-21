## Note
nid: 1611654865066
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1, checklater
markdown: false

### Front
Wie funktioniert <b>Projected Clustering?</b>

### Back
<b>Algorithmus:</b>
<div>
  (ähnlich k-means (neu ist blauer Schritt: in welche Dimensionen,
  bildet die Menge der Punkte um Clustermittelpunkt einen
  Cluster?))
  <div><img src=
  "paste-3c044b25b5a0d67cf730e3d2893306eb290d6e0d.jpg"></div>
</div>
<div>
  <b>Bestimmung der Dimension zu jedem Medoid:</b>
</div>
<div>
  Funktioniert wie \(k\)-Means, nur dass am Anfang jedes Schrittes
  die Dimensionen, in denen die Medoide signifikant sind, ermittelt
  werden müssen.
  <div>
    Man bestimmt für jede Dimension einzeln den Abstand zwischen
    Medioid \(m_i\) und den Objekten in seiner Locality
    \(\mathcal{L}_i\). Die Locality wurde als <b>Kugel mit Radius
    bis zum nächsten anderen Medioiden</b> vorgestellt.
  </div>
  <div><img src=
  "paste-d8fb8970b3a76458352f055d9399af143f54bff6.jpg"></div>
  <div>
    Man bezeichnet die durchschnittliche Distanz der Objekte in der
    Locality \(i\) mit Dimension \(j\) mit \(X_{i,j}\). Hier z. B.
    1. Cluster, 1. Dimension. Man sollte Dimension \(X_{1,1}\)
    enthalten haben, weil kompakter.
  </div>
  <div><img src=
  "paste-ccf2241238d1501a3f0afa6cf90d4adb550a31d1.jpg"></div>
  <div>
    Dann lässt sich der Durchschnitt berechnen, wobei \(d\) die
    Zahl der Dimensionen ist:
  </div>
  <div>
    \(Y_{i}=\frac{\sum_{j=i}^{d} X_{i, j}}{d}\)
  </div>
  <div><img src=
  "paste-f00353c8ee87fbfb65a9e3c5437e57c5f5c5be5c.jpg"></div>
  <div>
    Distanz sollte kürzer sein als
    Durchschnitt-Durchschnittsdistanz der Dimensionen (hier grün).
    Gilt \(X_{i,j} - Y_i\) ist negativ, dann ist die Dimension
    \(j\) wichtig für Medoid \(i\).
  </div>
  <div>
    Um den Effekt von Stauchungen in einer Dimension
    (unterschiedliche absolute Abstände bei verschiedenen Clustern)
    zu vermeiden, bereinigt man noch mit der Standardabweichung:
  </div>
  <div>
    \(\sigma_{i}=\sqrt{\frac{\sum_{j}\left(X_{i,
    j}-Y_{i}\right)^{2}}{d-1}}\).
  </div>
  <div>
    Man normalisiert dann:
  </div>
  <div>
    \(Z_{i, j}=\frac{X_{i, j}-Y_{i}}{\sigma_{i}}\).
  </div>
  <div>
    Sind die Daten in vielen Dimension ähnlich um \(m_i\) verteilt,
    dann ist Medoid ein brauchbarer Mittelpunkt für seine Locality.
  </div>
  <div>
    Dann sortiert man \(Z_{i,j}\) und ordnet jedem Cluster seine
    Dimensionen zu. (Bedingung, dass pro Cluster im Durchschnitt
    \(l\) Dimensionen ausgewählt werden, muss gewährleistet sein.)
  </div>
  <div>
    Einzelne Punkte werden Ihren Medoiden über die <b>Manhattan
    Segmental distance</b> zugeordnet. (Relevant, weil unfair, wenn
    ein Cluster z. B. 2 Dim. hätte und ein anderer nur 1 Dim.
    Cluster mit weniger Medoiden hätten einen Vorteil.)
  </div>
</div>
