## Note
nid: 1632814420878
model: Basic-d7a3e
tags: 07_association_rules
markdown: false

### Front
Warum ist FP-Tree für Projected Database i. d. R. kleiner als für
<b>Ausgangsdatenbestand</b>?

### Back
Angenommen p ist Item, das am seltensten in Transaktion vorkommt.
Projected Database für p ist klein, da es nur wenige Transaktionen
gibt, die p enthalten.
<div>
  Angenommen f ist sehr häufig vertreten in Transaktionen. Kommt f
  zwar in vielen Transaktionen vor, dann sind die Pfade sind kurz.
  Der FP-Tree damit klein. Die f-projected Database hat geringen
  Speicherbedarf.
</div>
