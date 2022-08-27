## Note
nid: 1620913683618
model: Basic-d7a3e-4ce08
tags: 04_fehlertoleranz, checklater, klausur
markdown: false

### Front
Wie lassen sich Ersatzkomponenten in einem <b>Fehler-toleranten
System</b> verwenden, bevor sie aktiviert werden?

### Back
<div>
  <div>
    <ul>
      <li><strong>Ungenutzte Redundanz</strong> Ersatzkomponenten
      führen keine sonstigen Funktionen aus und bleiben bis zur
      fehlerbedingten Aktivierung passiv.
      <li><strong>Gegenseitige Redundanz</strong> Ersatzkomponenten
      erbringen die von einer anderen Komponente zu unterstützende
      Funktionen, die Komponenten stehen sich gegenseitig als
      Reserve zur Verfügung. Ermöglicht abgestuften Leistungsabfall
      (<em>graceful degradation</em>)
      <li>Fremdgenutzte Redundanz: Ersatzkomponenten erbringen nur
      Funktionen, die nicht zum betreffendenden Subsystem gehören
      und im Fehlerfall bei niedriger Priorisierung ggf. verdrängt
      werden.
    </ul>
  </div>
</div>
