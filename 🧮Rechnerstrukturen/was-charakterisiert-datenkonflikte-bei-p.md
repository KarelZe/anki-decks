## Note
nid: 1627886259016
model: Basic-d7a3e
tags: 03_uebung_rs, 06_para_maschinenbefehl
markdown: false

### Front
Was charakterisiert <b>Datenkonflikte</b> bei <b>Pipelines</b>?

### Back
<div>
  <div>
    <ul>
      <li>Ergeben sich aus <strong>Datenabhängigkeiten</strong>
      zwischen Befehlen im Programm
      <li>Konflikte aufgrund <strong>echter
      Datenabhängigkeiten</strong> → Instruktion benötigt Ergebnis
      vorheriger Instruktion, die ist aber nicht fertig.
      <li>Konflikte aufgrund von
      <strong>Namensabhängigkeiten</strong> → Verwendung von
      Registernamen. Unproblematisch bei RISC wegen frühem Lesen
      und spätem Schreiben.
    </ul>
  </div>
</div>
