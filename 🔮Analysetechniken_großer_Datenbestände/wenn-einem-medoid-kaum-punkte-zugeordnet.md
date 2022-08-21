## Note
nid: 1610448176805
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_1
markdown: false

### Front
<p>Wenn einem Medoid kaum Punkte zugeordnet werden können, handelt es sich dabei vermutlich um einen Ausreiser oder Teil eines anderen Punkts.</p><p>Welche <b>Ansätze</b> bestehen um diesen <b>Medoid</b> durch einen <b>anderen Punkt</b> zu ersetzen?</p>

### Back
<p>

</p><ul style="text-indent: 0px;"><li style="letter-spacing: normal; text-transform: none; white-space: normal; word-spacing: 0px;"><p style="">Medoid des Clusters mit den <b>wenigsten Punkten ersetzen</b>.</p></li><li style=""><p style="">Medoid eines Cluster mit weniger als \(N/k \times \text{minDev}\)<span style="letter-spacing: normal; text-transform: none; white-space: normal; word-spacing: 0px;"> Punkten ersetzen</span>. \(\text{minDev}\) ist Konstante.</p></li></ul>

<p></p>
