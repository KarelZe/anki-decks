# Note
```
guid: pA7+y.sPf3
notetype: Basic-d7a3e-4ce08
```

### Tags
```
04_koheraenz
11_para_block_prozess
```

## Front
Was bedeuten die Zustände <b>Modified</b> und <b>Exclusive
Modified</b>?

## Back
Der Speicherblock existiert als Kopie nur in der Zeile des
betrachteten Caches. Er wurde nach dem Laden verändert.
<div>
  Der Prozessor kann lesend und schreibend zugreifen, ohne den Bus
  benutzen zu müssen.
</div>
<div>
  Der Prozessor beobachtet einen Lese- oder Schreibzugriff eines
  anderen Prozessors auf einen Block, der in seinem Cache geladen
  ist (Snoop-Hit), muss dieser in den Hauptspeicher zurückkopiert
  werden.
</div>
<div>
  <div>
    <div>
      <div>
        <ul>
          <li>Snoop-Hit on a Read: Übergang von Modified → Shared
          <li>Snoop-Hit on Write or Read with Itend to Modify:
          Übergang von Modified → Invalid
        </ul>
      </div>
    </div>
  </div>
</div>
<div>
  Der Prozessor, der den Block aus dem Hauptspeicher holen will,
  wird mithilfe des Retry-Signals darüber informiert, dass zunächst
  ein Zurückschreiben erforderlich ist.
</div>
<div>
  <b>Write Hit:</b> Ist Block in Cache vorhanden, hat man einen
  Read-Hit oder Write-Hit, man bleibt im Zustand Modified.
</div>
<div>
  <b>Write-Miss m. E.</b> Führt man Schreiboperation durch und die
  Adresse befindet sich nicht bereits im Cache, aber eine
  Cachezeile im Zustand Modified ausgewählt wird, in die der Block
  geladen, der zu ändern ist, geladen werden soll, so bleibt die
  Cachezeile im Zustand modified.
</div>
<div>
  Cachezeile wird in Hauptspeicher zurückgeschrieben.
</div>
<div>
  Cache-Zeile mit gleicher Blockadresse in anderen Caches werden
  invalidiert.
</div>
<div>
  Lesezugriff führt zu Fehlzugriff, weil eine Cache-Zeile
  ausgewählt wird, in die der Block geladen wird, welche Zustand
  modified hat, muss der alte Block zunächst in den Hauptspeicher
  geladen werden. Der Block, der geschrieben wird, ist dann im
  Zustand modified und Übergang in Zustand exclusive.
</div>
<div>
  Ist bei einer Leseoperation der Block bereits in anderen Caches
  vorhanden und die Cachezeile, in die der Block geladen wird, im
  Zustand <b>modified</b>, dann geht man in den Zustand
  <b>shared</b>.
</div>
