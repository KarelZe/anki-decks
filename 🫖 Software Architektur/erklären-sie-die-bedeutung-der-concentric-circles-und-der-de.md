# Note
```
guid: A+Ct3J%;mA
notetype: Basic-d7a3e-4ce08
```

### Tags
```
04_Architectural_Reuse
architecture
architecture_4
```

## Front
Erklären Sie die Bedeutung der <b>concentric circles</b> und der
<b>dependency rules</b> in der <b>Clean Architecture Reference
Architecture</b>.
<div><img src="paste-779a4f0c79c1acc4ded9362c5f1e0a0cc007ccf2.jpg"></div>

## Back
<b>Concentric circles</b> repräsentieren verschiedene Bereiche der
Software.
<div>
  Außere Kreise beschreiben dabei Mechanismen. Innere Kreise sind
  Entitäten z. B. Elementare Datenstrukturen. Dann folgen Use
  Cases. Äußere Kreise ändern sich sehr oft. Kern bleibt stabil.
  Äußere Kreise dürfen damit keinen Einfluss auf innere haben.
</div>
<div>
  <b>Dependency rule</b> zeigt die Abhängigkeit. Die Abhängigkeit
  des Sourcecodes zeigt dabei nach innen. Sodass sich Änderung z.
  B. an Frameworks außen nicht auf Kern auswirkt.
</div>
<div>
  Die Regel gilt für Funktionen, Klassen, Variablen, Datenformate.
</div>
