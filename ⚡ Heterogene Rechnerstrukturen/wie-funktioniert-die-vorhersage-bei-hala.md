## Note
nid: 1613849091140
model: Basic-d7a3e-4ce08
tags: het_rs::09_programmierung
markdown: false

### Front
Wie funktioniert die <b>Vorhersage</b> bei <b>HALadapt</b>?

### Back
<div>
  <div>
    <ul>
      <li>Online-Learning-Verfahren
      <li>Bei einer Laufzeitanfrage wird Datenbank überprüft
      <li>Gibt es noch keine Messungen, wird ein Check angefordert,
      Messwert danach gespeichert
      <li>Ansosten wird überprüft, ob es Messungen zur Problemgröße
      gibt
        <ul>
          <li>Falls ja, wird Wert zurückgegeben
          <li>Falls nein, wird nach Möglichkeiten der Interpolation
          gesucht.
        </ul>
    </ul>
  </div>
</div>
