# Note
```
guid: FR3m.Sg;Nq
notetype: Basic-d7a3e-4ce08
```

### Tags
```
04_koheraenz
11_para_block_prozess
```

## Front
Wodurch findet ein Übergang vom Status Invalidate in die Zustände
<b>Shared</b>, <b>Exclusive</b> und <b>Modified</b> statt?
<div><img src="81526403.png"></div>

## Back
<div>
  Lese- und Schreiboperationen auf eine Speicherziel veranlassen
  die Cache-Steuerung, den Speicherblock in die Cache-Zeile zu
  laden. → Aussenden invalidate-Signal.
</div>
<div>
  Die anderen Cache-Steuerungen, die den Cache beobachten, zeigen
  an, dass dieser Block gespeichert ist → Aussenden shared-read
  miss oder nicht → Aussenden exclusive read miss.
</div>
<div>
  Bei Write-Miss erfolgt Übergang in Zustand M. → Aussenden
  Invalidate Signal, das von anderen ausgesendet wird
</div>
