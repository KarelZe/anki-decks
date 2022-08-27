## Note
nid: 1616241190382
model: Basic-b122e-20a86
tags: 12_relevante_objekte_empfehlen
markdown: false

### Front
Skizzieren und erklären Sie die Architektur der <b>Suchmaschine
Google.</b>

### Back
<ol>
  <li><strong><font color="#FF0000">Komponenten zum
  Crawling:</font></strong> Der URL-Server schickt eine Liste mit
  zu suchenden Webseiten an die Crawler. Verteilte Crawler laden
  Webseiten herunter. Der Store-Server komprimiert die Webseiten
  und legt sie im Webpage-Repository mit einer doc id ab.
  <li><strong>Komponenten zum Indizieren von Daten</strong> Der
  Indexer liest das Repository, dekomprimiert die Webseiten und
  extrahiert aus den Webseiten Worttreffer mit Informationen zu
  Schriftgröße, Großschreibung etc. (hits) und speichert sie in den
  <em>barrels</em> ab. Weiterhin werden alle Links extrahiert und
  Linkziel, der Linktext und die Linkquelle in <em>Anchors
  Files</em> gespeichert. Der URL-Resolver liest die Anchor Files,
  konvertiert die Links in absolute Links und generiert doc Ids.
  Die Anchor-Texts werden ebenfalls mit abgelegt im Forward Index.
  Der Sorter sortiert die Barrels nach wordIDs, um einen
  invertierten Index zu erstellen. Weiterhin besteht ein Lexikon,
  das neu aus dem Indexer generiert wird. Es wird dann vom
  <em>Searcher</em> verwendet, um mit dem invertierten Index und
  PageRank Suchanfragen zu beantworten.
  <li><strong><font color="#0000FF">Komponenten zum Bewerten der
  Wichtigkeit</font></strong> Anhand der Links wird eine
  Link-Datenbank aufgebaut, woraus dann der Page-Rank für alle
  Dokumente ermittelt wird (vgl. The anatomy of a large-scale
  hypertext).
</ol>
<div><img src=
"Untitled-1405144014d2316248d6033c5f2f6164ef75ede0.png"></div>
