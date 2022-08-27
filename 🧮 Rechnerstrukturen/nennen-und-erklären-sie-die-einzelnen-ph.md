## Note
nid: 1627644101830
model: Basic-d7a3e-4ce08
tags: 04_uebung, checklater, rs::04_uebung
markdown: false

### Front
Nennen und erklären Sie die einzelnen <b>Phasen</b> des
<b>Parallelisierungsprozesses</b>.

### Back
<div>
  <div>
    <ol>
      <li><strong>Dekomposition</strong> (oder Aufteilung) der
      Berechnung in Tasks → Granularität, möglicherweise dynamische
      Anzahl an Tasks
      <li><strong>Zuweisung</strong> der Tasks zu Prozessen →
      Lastverteilung, geringe Kommunikation
      <li><strong>Zusammenführung (Orchestration)</strong>
      Festlegung des notwendigen Datenzugriffs, der Kommunikation
      und der Synchronisation zwischen den Prozessen → Auswahl des
      passenden Programmiermodells
      <li><strong>Abbildung</strong> der Prozesse auf die
      Prozessoren
    </ol>
  </div>
</div>
