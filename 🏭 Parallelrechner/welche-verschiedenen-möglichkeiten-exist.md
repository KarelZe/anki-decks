## Note
nid: 1602352518796
model: Basic-b122e-20a86
tags: 5_2_open_mp
markdown: false

### Front
Welche verschiedenen Möglichkeiten existieren bei OpenMP, um Chunks einzelnen Teams zuzuweisen?

### Back
<ul>
  <li>
    <div>
      <strong>static:</strong> Iterationen werdne in Stücke der
      Größe chunk unterteilt. Die Stücke werden statisch den
      threads in einem team zugewiesen.
    </div>
  <li>
    <div>
      <strong>dynamic:</strong> Iterationen werden in Stücke der
      Größe chunk unterteilt. Sobald ein thread einen Brocken des
      Iterationsraums abgearbeitet hat, erhält er dynamisch den
      nächsten Brocken.
    </div>
  <li>
    <div>
      <strong>guided:</strong> Jeder thread bekommt ein Stück der
      Größe chunk. Ist ein thread fertig, bekommt er ein neues
      Stück, dessen Größe abfällt.
    </div>
  <li>
    <div>
      <strong>runtime:</strong> Schedule durch Umgebungsvariablen
      "OMP_SCHEDULE" bestimmt.
    </div>
    <div><img src= 
    "paste-f7b574f2d69242d9fd41ed9aa62fce8bd548ef28.jpg"></div>
</ul>
