# Note
```
guid: A!?AxUB#Wv
notetype: Basic-b122e-20a86
```

### Tags
```
2_3_parallelrechner
```

## Front
Was versteht man unter <b>False sharing</b>?

## Back
Verschiedene Datenwörter, die innerhalb einer Seite liegen, werden von verschiedenen Prozessoren z. B. für Schreibzugriffe benötigt.<div>
</div><div>Da die Kohärenzmechanismen immer nur die gesamte Seite betreffen, muss die Seite vor jedem Schreibzugriff dem anderen Prozessor entzogen und schließend erneut übertragen werden.</div><div>
</div><div>Bei mehrfachen Schreibzugriffen kommt es nicht nur zu häufigen Blockierungen der Prozessoren, sondern auch zum sogenannten Flattern (<i>thrashing</i>), da die Seite immer wieder übers Netz übertragen werden muss.</div>
