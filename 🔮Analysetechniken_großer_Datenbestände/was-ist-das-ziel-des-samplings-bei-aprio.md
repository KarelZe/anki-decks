## Note
nid: 1608984957069
model: Basic-d7a3e
tags: 07_association_rules
markdown: false

### Front
<p>Was ist das <b>Ziel</b> des <b>Samplings</b> bei <b>Apriori</b>?</p>

### Back
Weniger Schritte über die Datenbank.
<div>
  <b>Intutition</b>:
</div>
<div>
  Problem ist, dass Apriori level-weise arbeitet, also für jede
  Größe an Frequent Itemsets erst deren Kandidaten erzeugt, die
  dann mit der Datenbank geprüft werden. Eigentlich ist man ja aber
  nur an maximalen Frequent Itemsets interessiert! Etwa braucht man
  für Candidate Itemsets der Größe \((k+1)\), \((k+1)\) Schritte
  über die Datenbank. Deshalb will man auf Aufwahl arbeiten, die in
  Arbeitsspeicher passt.
</div>
<div>
  <div>
    Man sucht zunächst negative Border auf Stichprobe. Kennt man
    diese, wird erst auf vollem Datenbestand gearbeitet.
  </div>
</div>
