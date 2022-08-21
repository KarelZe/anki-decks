## Note
nid: 1612168765684
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Warum funktionieren klassische Distanzmaße z. B. euklidische Distanz schlecht bei kategorischen Daten? Erklären Sie mit Beispiel.

### Back
<div>
  Gekaufte Sortimentsartikel werden in Bit-Vektor mit Einsen
  codiert, nicht gekaufte Artikel mit Nullen.
</div>
<div>
  Wird ein Bit-Vektor, der ganz am Anfang eine 1 und ansonsten nur
  0 enthält nun mit einem Vektor verglichen der ganz am Ende eine 1
  und ansonsten Nullen hat.
</div>
<div>
  So sind beide Vektoren ähnlich. Die Vektoren stimmen aber nur in
  den Items überein, die nicht gekauft wurden, was nicht hilfreich
  ist.
</div>
