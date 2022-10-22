# Note
```
guid: v6|jX?~Z!z
notetype: Basic-d7a3e-4ce08
```

### Tags
```
03_uebung_rs
06_para_maschinenbefehl
```

## Front
Was charakterisiert <b>Datenkonflikte</b> bei <b>Pipelines</b>?

## Back
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
