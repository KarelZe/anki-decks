# Note
```
guid: xT,3AEqpA_
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
klausur
```

## Front
Müssen die Pipelines superskalarer Prozessoren zwingend nach dem "out of order"-Prinzip arbeiten? Erfordern "out of order"-Pipelines zwingend superskalare Prozessoren? Begründen Sie Ihre Antwort.

## Back
Nein. Superskalare Prozessoren können theoretisch auch "in order"
parallel arbeiten, wenn nur solche Befehle parallel ausgeführt
werden, deren Ausführung auch "in order" abgeschlossen wird.
<div>
  Nein. Befehle können, soweit es ihre Abhängigkeiten zulassen,
  auch auf einer skalaren Architektur beliebig verschoben werden.
  Dies bringt in den meisten Fällen allerdings keinen Vorteil mit
  sich. Durch das Vorziehen von Ladebefehlen könnte sich zum
  Beispiel ein Vorteil ergeben.
</div>
