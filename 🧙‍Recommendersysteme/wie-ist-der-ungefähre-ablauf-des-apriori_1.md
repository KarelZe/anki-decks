## Note
nid: 1588100459814
model: Basic-b122e
tags: 02_assoziationsregeln
markdown: false

### Front
Wie ist der ungefähre Ablauf des <b>Apriori-Algorithmus</b>?

### Back
<div>
  <ol>
    <li>
      <div>
        Bilde alle 1-elementigen , Produktkombinationen" \(L[1]\),
        die “oft genug” (support erreicht) miteinander vorkommen.
      </div>
    <li>
      <div>
        Bilde aus den 1-elementigen “Produktkombinationen”
      </div>
      <ol>
        <li>möglichen 2-elementigen Produktkombinationen \(C[2]\)
        (Kandidatenmenge \(C[2]\))
        <li>entfernen hier aus \(C[2]\) die Kombinationen, die
        nicht oft genug ( → support) vorkommen und nenne die
        verbliebene Menge \(L[2]\)
      </ol>
    <li>
      <div>
        Bilde aus den 2-elementigen Produktkombinationen
      </div>
      <ol>
        <li>möglichen 3-elementigen Produktkombinationen \(C[3]\)
        (Kandidatenmenge \(C[3]\) ) und zwar dadurch, dass alle
        2-elementigen Kombinationen aus \(L[2]\) genau dann
        miteinander kombiniert werden, wenn diese mindestens 1
        Element gemeinsam haben.
        <li>entfernen aus der Kandidatenmenge \(C[3]\) die
        Kombinationen, die nicht oft genug (→ support) vorkommen
        und nenne die verbliebene Menge \(L[3]\)
      </ol>
    <li>
      <div>
        Bilde aus den 3-elementigen Produktkombinationen
      </div>
      <ol>
        <li>möglichen 4-elementigen Produktkombinationen \(C[4]\)
        (Kandidatenmenge \(C[4]\)) und zwar dadurch, dass alle
        3-elementigen Kombinationen aus \(L[3]\) genau dann
        miteinander kombiniert werden, wenn diese mindestens 2
        Elemente gemeinsam haben.
        <li>entfernen aus der Kandidatenmenge \(C[4]\) die
        Kombinationen, die nicht oft genug (support) vorkommen und
        nenne die verbliebene Menge \(L[4]\)
      </ol>
    <li>
      <div>
        \(5 \cdots n\) Wiederhole solange, bis \(L[n]\) leer ist
      </div>
    <li>
      <div>
        \(\mathrm{N}+1:\) Gib \(L[1] \cup L[2] \cup \cdots \cup
        L[n]\) zurück.
      </div>
  </ol>
</div>
