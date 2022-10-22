# Note
```
guid: vZQgAEEn9X
notetype: Basic-d7a3e-4ce08
```

### Tags
```
04_koheraenz
```

## Front
Welche Synchronisationsmechanmismen sind für kleine Systeme / geringe Blockierungen geeignet? Welche für große Systeme / häufige Blockierungen?

## Back
<div>
  <strong>Geringe Blockierung</strong>
</div>
<ol>
  <li>Nicht unterbrechbare Instruktion(sfolge): test-and-set
  <li>Atomare Abarbeitung (read/modify/write)
</ol>
<div>
  <strong>Häufige Blockierung</strong>
</div>
<ol>
  <li>Komplexe Synchronisationsmechanismen
  <li>Spin Locks
  <li>Barriers
</ol>
