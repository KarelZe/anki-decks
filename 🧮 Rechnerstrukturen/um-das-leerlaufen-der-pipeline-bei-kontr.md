## Note
nid: 1628229829288
model: Basic-d7a3e-4ce08
tags: 03_uebung, 03_uebung_rs, checklater, klausur
markdown: false

### Front
Um das Leerlaufen der Pipeline bei Kontrollflussbefehlen zu
vermeiden existieren statitische sowie dynamische Techniken.
<div>
  Nennen Sie diese und stellen Sie die wesentlichen Unterschiede
  gegenüber.
</div>

### Back
<div>
  <div>
    <div>
      <strong>Statische Vorhersage / Prädikation</strong>
    </div>
    <ul>
      <li>Richtung der Vorhersage für Befehl <b>immer gleich</b>
      <li>Always taken, always not taken
      <li>Verwendete Technik:
        <ul>
          <li>Compiler-gestützt
          <li>Verzweigungsbefehle werden eliminiert. Zur Laufzeit
          wird Verzweigungsbedingung ausgewertet. Das Ergebnis der
          Berechnung wird gültig, wenn die Bedingung erfüllt ist,
          ansonsten wird der Zustand der Maschine nicht verändert,
          d. h. der Befehlt hat die Wirkung einer Leeroperation
        </ul>
    </ul>
    <div>
      <strong>Dynamische Sprungvorhersage / Prädiktion</strong>
    </div>
    <ul>
      <li>Vorhersage aufgrund von <b>bisherigem Programmablauf</b>
      <li>Sprungbefehle werden ausgeführt. Nächste Befehle werden
      entsprechend der Vorhersage über den Sprungausgang spekulativ
      geladen und ausgeführt.
      <li>Verwendete Technik:
        <ul>
          <li>Sprungzieltabelle, Prädiktor(en)
        </ul>
    </ul>
  </div>
</div>
