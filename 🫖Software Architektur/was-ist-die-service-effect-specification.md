## Note
nid: 1593329215363
model: Basic-d7a3e
tags: 05_modelling_quality, performance
markdown: false

### Front
Was ist die <b>Service Effect Specification</b>?

### Back
<p>Die <b>Service Effect Specification</b> beschreibt das Verhalten
in einer Komponente bei Aufruf einer Operation dieser Komponente
auf einer sehr abstrakten Ebene indem sie die Beziehung zwischen
aufrufendem Service und benötigten Diensten einer Komponente
spezifiziert. Dient der Architekturanalyse.
<p>Enthält eine <b>Abstraktion des Kontrollflusses</b> der
Komponente.
<p>Enthält <b>abstrakte Informationen</b> zum inneren
<b>Komponentenverhalten</b>.
<p>Annotiert mit den <b>Übergangswahrscheinlichkeiten</b>, um eine
<b>Wahrscheinlichkeit eines Ausfalls</b> unter Last vorherzusagen.
<p><b>Beispiel</b>:
<p><img src="paste-3cabb18e66e949e9d37472b3530941ba81fdcc1b.jpg">
<p>(Angelehnt an Aktivitätsdiagramme. Schwarze Kreise sind Start-
und Endzustand. In <<>> steht, um was für Art von
Aufruf es sich handelt z. B. Loop Action. Internal Action
abstrahiert Algorithmus.)
<p>Man weiß nicht, wie oft ich Branch wähle hängt von
Benutzungsprofil ab. Wie lange externe Aufrufe dauern, ist
ebenfalls unbekannt, weswegen nur Parameter / keine konkreten
Werte.
<p><img src="paste-5fad3269fd792f862b1ee487adb1fbdd23677334.jpg">
