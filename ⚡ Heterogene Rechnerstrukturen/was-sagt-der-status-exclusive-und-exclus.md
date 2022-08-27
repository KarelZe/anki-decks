## Note
nid: 1611761090093
model: Basic-d7a3e-4ce08
tags: 04_koheraenz, 11_para_block_prozess
markdown: false

### Front
Was sagt der Status <b>Exclusive</b> und <b>Exclusive
Unmodified</b> aus?

### Back
<div>
  Der Speicherblock existert als Kopie nur in der Zeile des
  betrachteten Caches.
</div>
<div>
  Es wurde ein Speicherblock <b>gelesen</b> und in eine Cachezeile
  geladen. Es existiert <b>keine</b> weitere Kopie in einem anderen
  Cache. (Exclusive Read Miss). Der Prozessor kann dann lesen und
  schreibend darauf zugreifen, ohne den Bus benutzen zu müssen.
</div>
<div>
  Für <b>Schreibzugriffe</b> wird in den Zustand M gewechselt.
  Andere Caches sind nicht betroffen.
</div>
<div>
  Ist Speicherblock im Cache vorhanden (Write Hit) wechselt man in
  Zustand Modified.
</div>
<div>
  Ist Speicherblock nicht im Cache vorhanden (Write Miss m. E.)
  wird ausgewählte Cachezeile überschrieben mit neuem
  Speicherblock. Entsprechend werden die Signale ausgesendet.
</div><img src="31380672.png">
