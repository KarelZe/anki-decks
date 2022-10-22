# Note
```
guid: M=4J~k5Sa0
notetype: Basic-b122e-20a86
```

### Tags
```
02_assoziationsregeln
```

## Front
Wie ist der ungefähre Ablauf des <b>Apriori-Algorithmus</b>?

## Back
<div><ol><li><div>Bilde alle 1-elementigen , Produktkombinationen" \(L[1]\), die “oft genug” (support erreicht) miteinander vorkommen.</div></li>
<li>
<div>Bilde aus den 1-elementigen “Produktkombinationen” </div>
<ol>
<li>möglichen 2-elementigen Produktkombinationen \(C[2]\) (Kandidatenmenge \(C[2]\))</li>
<li>entfernen hier aus \(C[2]\) die Kombinationen, die nicht oft genug ( → support) vorkommen und nenne die verbliebene Menge \(L[2]\)</li></ol></li>
<li>
<div>Bilde aus den 2-elementigen Produktkombinationen </div>
<ol>
<li>möglichen 3-elementigen Produktkombinationen \(C[3]\)

(Kandidatenmenge \(C[3]\) ) und zwar dadurch, dass alle 2-elementigen Kombinationen aus \(L[2]\) genau dann miteinander kombiniert werden, wenn diese mindestens 1 Element gemeinsam haben.</li>
<li>entfernen aus der Kandidatenmenge \(C[3]\) die Kombinationen, die nicht oft genug (→ support) vorkommen und nenne die verbliebene Menge \(L[3]\)</li></ol></li>
<li>
<div>Bilde aus den 3-elementigen Produktkombinationen </div>
<ol>
<li>möglichen 4-elementigen Produktkombinationen \(C[4]\) (Kandidatenmenge \(C[4]\)) und zwar dadurch, dass alle 3-elementigen Kombinationen aus \(L[3]\) genau dann miteinander kombiniert werden, wenn diese mindestens 2 Elemente gemeinsam haben.</li>
<li>entfernen aus der Kandidatenmenge \(C[4]\) die Kombinationen, die nicht oft genug (support) vorkommen und nenne die verbliebene Menge \(L[4]\)</li></ol></li>
<li><div>\(5 \cdots n\) Wiederhole solange, bis \(L[n]\) leer ist</div></li>
<li><div>\(\mathrm{N}+1:\) Gib \(L[1] \cup L[2] \cup \cdots \cup L[n]\) zurück.</div></li></ol></div>
