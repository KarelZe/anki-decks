# Note
```
guid: nRsp*bdOiH
notetype: Basic-d7a3e-4ce08
```

### Tags
```
04_koheraenz
11_para_block_prozess
```

## Front
Wodurch findet ein Übergang vom Status Shared in die Zustände
Invalidate, Exclusive und Modified statt?<img src="98480347.png">

## Back
<div>
  Lesezugriff auf Cache-Zeile durchführen (Read-Hit). Da Datum auch
  in anderen Caches vorliegt, ist man im Zustand shared → nur Lesen
  verändert Zustand nicht.
</div>
<div>
  Schreibzugriff auf die Cache-Zeile (Write-Hit) verändert
  Cachezeile → Übergang in Zustand Modified. Und Aussenden des
  invalidate-Signals, woraufhin die Caches, bei denen diese
  Cache-Zeile ebenfalls im Zustand S ist, diese als ungültig
  kennzeichnen (Zustand I). Cachzeile liegt nämlich wegen
  ursprünglichen Zustand shared auch in anderen Caches.
</div>
<div>
  Lesezugriff (shared read miss) wird von Prozessor beobachtet. D.
  h. Datenwert liegt nicht im Cache (Fehlzugriff), soll aber in
  eine Cachezeile, die im Zustand shared ist, geschrieben /
  aktualisiert werden. Bekommt anderer Prozessor, das zu lesender
  Speicherblock bereits in anderem Cache vorhanden ist, schickt er
  shared Signal → shared-Read Miss mit Ersetzung
</div>
