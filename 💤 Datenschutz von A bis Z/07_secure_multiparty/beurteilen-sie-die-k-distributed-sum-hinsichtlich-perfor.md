# Note
```
guid: fsU;/l?%Wf
notetype: Basic-9c783
```

### Tags
```
datenschutz::07_secure_multiparty
```

## Front
Beurteilen Sie die \(k\)-distributed sum hinsichtlich Performanz und Sicherheit.

## Back
<b>Sicherheit:</b>
<ul>
  <li>Arbeiten alle Teilnehmer korrekt, dann ist Protokoll sicher
  <li>Wenn der Protokoll-Initiator falsch arbeitet, stimmt Ergebnis
  nicht, Privatheit aber gewahrt
  <li>Wenn zwei Teilnehmer kooperieren, bleibt die Privatheit der
  Daten gewahrt, da ein Teilnehmer jeweils nur Datensegmente der
  anderen Teilnehmer hat
</ul><b>Performanz:</b>
<ul>
  <li>Schlecht / praktisch unpraktikabel. Einerseits \(k\) Runden
  des Verfahrens. Anderseits \(k^*(k-1)\) Kommunikationsvorgänge,
  um die zufälligen Segmente auf andere Nutzer zufällig
  aufzuteilen. Rechenaufwand vernachlässigbar.
</ul>
