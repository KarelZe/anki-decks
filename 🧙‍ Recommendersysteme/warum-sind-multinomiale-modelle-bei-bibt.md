## Note
nid: 1616312550466
model: Basic-b122e-20a86
tags: 08_bib_tip
markdown: false

### Front
Warum sind <b>multinomiale Modelle</b> bei <b>BibTip</b> notwendig?

### Back
<ul>
  <li>Es besteht ein cold start Problem bei neuen Dokumenten im
  Bibliothekskatalog.
  <li>Bei sehr kleinen Einkaufskörben und einer Vielzahl von
  Dokumenten braucht man sehr lange bis man sehr viele
  Überprüfungen für die Dokumente durchgeführt hat.
  <li>Statstistische Tests für Verteilungen sind aber nur
  verlässlich für <strong>sehr viele Treffer je Dokument</strong>
  z. B. Schätzen Mittelwert für LSD-Verteilung
  <li>Man braucht also Statistiken, die sich für sehr kleine Mengen
  an Treffer je Dokument eignen.
  <li>POSICI / POMICI sind Varianten davon.
</ul>
