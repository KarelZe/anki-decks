## Note
nid: 1602350072212
model: Basic-b122e
tags: Eigene
markdown: false

### Front
Vergleichen Sie <b>strikte</b> mit <b>sequentielle Konsistenz</b>

### Back
<ul>
<li>
<div><strong>Strikte Konsistenz</strong></div>
<ul>
<li>
<div>konsequentes Konsistenzmodell</div>
</li>
<li>
<div>"Jeder Read liefert als Ergebnis den Wert der letzten Write-Operation zurück."</div>
</li>
<li>
<div>Hierfür ist absolute, globale Zeit notwendig.</div>
</li>
<li>
<div>Unmöglich in einem verteilten System implementierbar.</div>
<div><img src="paste-97180ca30dbaa6fa4b7e523436e185b870f28744.jpg">

</div></li>
</ul>
</li>
<li>
<div><strong>Sequentielle Konsistenz</strong></div>
<ul>
<li>
<div>Etwas schwächeres Modell, aber implementierbar</div>
</li>
<li>
<div>"Wenn mehrere nebenläufige Prozesse auf Daten zugreifen, dann ist jede gültige Kombination von Read und Write Operationen akzeptabel, solange alle Prozesse dieselbe Folge sehen.</div>
<div><img src="paste-173c6b80d89bc7cbc46e3af3c90f1ace0ee04c07.jpg">
</div></li></ul>
</li></ul>
