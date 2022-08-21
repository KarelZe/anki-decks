## Note
nid: 1632656423465
model: Basic-d7a3e
tags: 03_raeumliche_index_strukturen, checklater
markdown: false

### Front
Warum verwendet man einen <b>Index</b> bei Datenstrukturen?

### Back
Daten sind seitenweise angeordnet. Um auf ein Datenobjekt zugreifen
zu können z. B. für Selektionen muss immer gesamte Seite in
Speicher geladen werden. Das Laden der Seite ist sehr teuer.
<div>
  Naiv würde man alle Seiten durchlaufen, was teuer ist um ein
  bestimmtes Datenobjekt zu finden. Man baut deshalb Indizes auf,
  mit dem man von Vornherein Datenobjekte auf Seiten lokalisieren
  kann. Es wird dann nur noch jeweilige Seite geladen und innerhalb
  dieser das Datenobjekt gesucht.
</div>
<div>
  <div>
    <div>
      <b>Beispiel eindimensionaler Index:</b>
    </div>
    <div>
      Man sucht gpa gleich 1. Index liegt als B+-tree (innere
      Knoten enthalten nur Schlüssel bei B+ Tree; Blätter
      Datenelemente) vor. 1 Eintrag gibt dabei den gpa des
      Datenobjekts an und das zweite Tupel (Seite, Position
      innerhalb Seite).
    </div>
    <div><img src= 
    "paste-9f872955e127c194c5ef7e6cd73c565d5bbf0cc8.jpg"></div>
  </div>
  <div>
    <b>Seiten im Hauptspeicher:</b>
  </div>
  <div><img src=
  "paste-57798f9682057a976091e1cfb271d4f4c3cb5e75.jpg"></div>
  <div>
    Man weiß bereits anhand von Index, dass es kein Objekt gibt,
    dass die Eigenschaft erfülllt und braucht deshalb die Seiten
    gar nicht zu laden.
  </div>
  <div>
    <b>Beispiel mehrdimensionaler Index:</b>
  </div>
  <div>
    Index für (gpa, name):
  </div>
  <div><img src=
  "paste-0e68149a802dbc21f1876d4142f8b1d25f338bd0.jpg"></div>
  <div><img src=
  "paste-bc2c11ba1763cf53f92b735dca8110594d84cd59.jpg"></div>
</div>
