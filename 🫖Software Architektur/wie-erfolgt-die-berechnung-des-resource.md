## Note
nid: 1634995915534
model: Basic-d7a3e
tags: 05_modelling_quality, performance
markdown: false

### Front
Wie erfolgt die Berechnung des Resource Demand in Palladio?

### Back
In Palladio muss der Komponentenentwickler den Resource Demand in
abstrakten Größen (<i>work units</i>) definieren z. B. Anzahl der
CPU Instruktionen / Anzahl der Bytes, die aus Speicher gelesen
werden.
<div>
  Die genaue Ausführungszeit wird dann für ein konkretes Resource
  Environment anhand der <i>work units</i> bestimmt.
</div>
