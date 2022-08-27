## Note
nid: 1617374137660
model: Basic-d7a3e-4ce08
tags: 12_Vektorverarbeitung
markdown: false

### Front
Welches <b>Problem</b> tut sich bei der <b>Vektorisierung</b> von
<b>Matrix-Multiplikationen</b> auf?

### Back
Die Elemente eines Vektors liegen nicht in aufeinanderfolgenden
Speicherzellen.
<div>
  Beispiel Matrix-Multiplikation einer \(3 \times 3\) Matrix:
</div>
<div><img src=
"paste-f2744e27331af2b18b3471da9d54e38acd973b29.jpg"></div>
<div>
  Bei spaltenweiser Ablage der Daten im Speicher ist der Stride für
  die Matrix C gleich 1 (oder 1 Doppelwort) und für die Matrix B
  gleich 3 (oder 3 Doppelwörter). Man greift also nicht auf
  zusammenhängende Speicherbereiche zu.
</div>
