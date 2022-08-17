## Note
nid: 1628142815544
model: Basic-d7a3e
tags: 07_multi_threading
markdown: false

### Front
Welche Aufgaben hat der <b>Compiler </b>bei <b>VLIW</b>?

### Back
<div>
  <div>
    <ul>
      <li><strong>Frontend:</strong> lexikalische, syntaktische und
      semantische Analyse
      <li>
        <strong>Code-Generierung:/Parallelisierung</strong>
        <ul>
          <li>Kontrollflussanalyse
          <li>Datenflussanalyse
          <li>Datenabhängigkeitsanalyse
        </ul>
      <li>
        <strong>Schleifenparallelisierung</strong>
        <ul>
          <li>Loop Unrolling
          <li>Software-Pipelining
        </ul>
      <li><strong>Scheduling:</strong> Packen der voneiander
      unabhängigen Befehle in breite Befehlswörter
    </ul>
  </div>
</div>
