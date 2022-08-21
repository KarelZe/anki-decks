## Note
nid: 1593328741959
model: Basic-d7a3e
tags: 05_modelling_quality, performance
markdown: false

### Front
Was ist die sogenannte <b>Ressource Demanding Service Effect
Specifications (RDSEFF)</b>?

### Back
<div>Das Palladio Komponentenmodell stellt mit dem RDSEFF eine Beschreibungssprache bereit, um den Kontrollfluss (z. B. Verzweigungen, Schleifen, Aufrufe externer Dienste) und der Ressourcennutzung der bereitgstellten Dienste zu modellieren.</div><div>
</div><ul>
<li><strong>RDSEFF</strong> ist eine Erweiterung der <strong>SEFF</strong> für die Performance Vorhersage.
</li>
<li>Palladio's component quality specification basiert darauf. </li>
<li>Jedes <strong>RDSEFF</strong> liefert eine parametrisierte Verhaltensbeschreibung und Qualitätsspezifikation für einen Komponentendienst:</li><ul>
<li>Aktivitäten werden durch Nodes dargestellt.</li>
<li>Der <i>resource demand</i> pro Aktivität kann festgelegt werden.</li></ul></ul><div>
</div><ul>

<li><strong>RDSEFF</strong> beschreibt:</li><ul>
<li>Wie ein Dienst Hardare/ Software nutzt?</li>
<li>Wie ein Dienst die für die Komponente benötigten Dienste aufruft?</li>
</ul>

</ul><div><b>Beispiele</b>: CPU Verbrauch oder Bytes, die auf Platte geschrieben werden.</div><div>
</div><div><img src="paste-b849751e75da5aa1a777b190b9e3780e5ac55d2f.jpg">
</div>
