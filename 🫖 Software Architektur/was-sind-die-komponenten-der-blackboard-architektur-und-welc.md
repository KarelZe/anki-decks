# Note
```
guid: DS{62A|17q
notetype: Basic-d7a3e-4ce08
```

### Tags
```
04_Architectural_Reuse
architecture
architecture_4
```

## Front
Was sind die Komponenten der <b>Blackboard-Architektur</b> und
welche Aufgaben übernehmen sie?

## Back
<div>
  <div>
    <div>
      <div>
        <ul>
          <li>Auf gemeinsame Datenstruktur schreiben mehrere
          Clients gleichzeitig.
        </ul>
      </div>
      <div>
        <strong>Knowledge Sources</strong>:
      </div>
      <ul>
        <li>Domänen-Wissen partitioniert in separate, unabhängige
        Berechnungen.
        <li>Reagiert auf Veränderungen im Blackboard.
      </ul>
      <div>
        <strong>Blackboard Data Structure</strong>:
      </div>
      <ul>
        <li>Gesamter Zustand der Problemlösung
        <li>Hierarchisch, nicht-homogen
        <li>Blackboard stellt nur sicher, dass es keine Schreib-
        und Lesekonflikte gibt.
      </ul>
      <div>
        <strong>Control</strong>: Im Modell, <b>Knowledge
        Sources</b> sind selbst aktivierend.
      </div>
    </div>
  </div>
</div>
<div>
  <b>Skizze:</b>
  <div><img src=
  "paste-fa30c799b94c8ba4af0c6b148621c9c95adf9e40.jpg"></div>
</div>
<div><img src="Blackboad_pattern_system_structure.png"></div>
<div>
  <ul>
    <li><b>blackboard:</b> strukturierter globaler Speicher, der
    Objekte des Lösungsraums enthält.
    <li><b>knowledge sources:</b> Spezialisierte Modeule mit ihrer
    eigenen Repräsentation
    <li><b>control component:</b> wählt, konfiguriert und führt
    Module / knowledge sources aus.
  </ul>
</div>
