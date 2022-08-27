## Note
nid: 1635064343004
model: Basic-d7a3e-4ce08
tags: 06_getting_data, performance
markdown: false

### Front
Nennen Sie häufige Fehler bei der Modellierung eines Systems für
<b>Performanz</b>- und <b>Verlässlichkeitsvorhersage</b>?

### Back
<ul>
  <li><b>Falscher Resource Demand:</b> z. B. weil Ressource auch
  durch anderweitig ausgelastet; Resource Demand verändert sich
  unter Last
  <li><b>Ungenaue Timer:</b> z. B. wenn Messung über Clock Ticks
  erfolgt und Prozess bei Multi-Prozessor auf andere CPU verschoben
  werden kann. Aber Timer suggeriert hohe Auflösung.
  <li><b>Fehlende Ressourcen:</b> Vergessene Ressourcen, die
  Performance beeinflussen z. B. Passive Ressourcen wie Thread
  Pools, Speicher
  <li><b>Keine Validierung:</b> Performanzmodelle sind eine
  Abstraktion des Realsystems, brauchen Validerung mit realen
  Messungen, da es Annahmen für das Verhalten von Komponenten und
  Diensten macht.
  <li><b>Modellierung zu vieler Details:</b> Zu viele modellierte
  Details, erfordern mehr gesammelte Informationen, erhöhen die
  Komplexität des Modells. Es wird schwieriger die Ursache für die
  Abweichung zwischen Vorhersage und Messung zu finden.
</ul>
