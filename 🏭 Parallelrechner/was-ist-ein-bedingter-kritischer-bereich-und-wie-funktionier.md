# Note
```
guid: FPq~;7KE5Z
notetype: Basic-b122e-20a86
```

### Tags
```
3_5_synchronisation
```

## Front
Was ist ein <b>bedingter kritischer Bereich</b> und wie
funktioniert er?

## Back
Ein durch eine Bedingungsvariable kontrollierter kritischer
Abschnitt.
<div>
  Der Eintritt in den kritischen Abschnitt wird von einer Bedingung
  abhängig gemacht. Die Bedingung wird selbst im kritischen Bereich
  ausgewertet.
  <div>
    Zu einem Zeitpunkt kann sich höchstens ein Prozess im
    kritischen Bereich befinden.
    <div>
      Bei Nichterfüllung der Bedingung: → Blockiert ein Prozess. d.
      h. Prozess reiht sich zu den wartenden Prozessen ein.
      <div>
        Bei Erfüllung der Bedingung: → Prozess nimmt an Wettbewerb
        um den Eintritt in den kritischen Bereich teil → Wettbewerb
        sollte fair sein.
      </div>
    </div>
  </div>
</div>
