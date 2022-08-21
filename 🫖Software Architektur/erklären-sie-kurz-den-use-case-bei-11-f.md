## Note
nid: 1635055702680
model: Basic-d7a3e
tags: 07_case_studies
markdown: false

### Front
Erklären Sie kurz den <b>Use Case</b> bei 1&1 für
<b>Palladio</b>.

### Back
1&1 verfügt über ein Service orientiertes System aus vielen Diensten. Hochverteilt über 2,000 hosts.<div>Es muss eine hohe Verfügbarkeit des Live-Systems garantiert werden. Mailsystem hat über 100 web services, die angeboten werden.</div><div>
</div><div>Experimente / Generierung von Last / QA Systeme wegen virtueller Hosts nicht ohne Weiteres möglich, da es keine sinnvolle Lasttreiber gibt.</div><div>
</div><div><b>Ansatz</b>:</div><div>Man wollte Monitoring-System validieren. Man wendet Performanz-Vorhersage (performance prediction) an, um das <b>erwartete Systemverhalten </b>aus dem gemonitorten Nutzerverhalten zu validieren. Daten aus dem Monitoring dienten als Input.</div><div>
<div><b>Ergebnisse</b>:</div></div><div>Vorhergesagte und tatsächliche Auslastung der Ressourcen weichen um 8.6 % ab. Es exisitieren keine Anomalien im System von  1&1.</div>
