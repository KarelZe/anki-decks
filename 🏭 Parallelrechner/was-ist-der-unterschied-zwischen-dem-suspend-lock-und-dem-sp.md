# Note
```
guid: mzRj06!bPn
notetype: Basic-b122e-20a86
```

### Tags
```
3_6_synchronisation_und_kommunikation
```

## Front
Was ist der Unterschied zwischen dem <b>suspend lock</b> und dem
<b>spin lock</b>?

## Back
<b>Suspend lock:</b> Betriebssystem verwaltet wartende
Prozesse/Threads und aktiviert erst bei Freigabe des kritischen
Bereichs einen der wartenden Prozesse/Threads
<div>
  <b>Spin lock:</b> Falls ein kritischer Bereich durch einen
  anderen Prozess oder Thread
</div>belegt ist, wird der swap Befehl solange wiederholt, bis der
kritische Bereich freigegeben wird = aktives Warten
