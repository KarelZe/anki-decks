## Note
nid: 1628063756063
model: Basic-d7a3e
tags: checklater, klausur
markdown: false

### Front
Müssen die Pipelines superskalarer Prozessoren zwingend nach dem "out of order"-Prinzip arbeiten? Erfordern "out of order"-Pipelines zwingend superskalare Prozessoren? Begründen Sie Ihre Antwort.

### Back
Nein. Superskalare Prozessoren können theoretisch auch "in order" parallel arbeiten, wenn nur solche Befehle parallel ausgeführt werden, deren Ausführung auch "in order" abgeschlossen wird. <div>
</div><div>Nein. Befehle können, soweit es ihre Abhängigkeiten zulassen, auch auf einer skalaren Architektur beliebig verschoben werden. Dies bringt in den meisten Fällen allerdings keinen Vorteil mit sich. Durch das Vorziehen von Ladebefehlen könnte sich zum Beispiel ein Vorteil ergeben.</div>
