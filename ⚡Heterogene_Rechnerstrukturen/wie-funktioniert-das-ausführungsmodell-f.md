## Note
nid: 1613913808318
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Wie funktioniert das <b>Ausführungsmodell Fork / Join</b>?

### Back
<div>
  <div>
    <ul>
      <li>Betritt ein Thread eine parallele Region, erzeugt er ein
      Thread-Team <em>(fork)</em> und wird zu deren Master-Thread.
      <li>Jeder Thread führt Code der Regions aus.
      <li>Implizite Barriere am Ende der Region <em>(join)</em>
      <li>Nur der Master-Thread rechnet nach der parallelen Region
      weiter.
      <li><img src= 
      "paste-8f4a28c393446270a7a008cacc0a70d7a22159a6.jpg">
    </ul>
  </div>
</div>
