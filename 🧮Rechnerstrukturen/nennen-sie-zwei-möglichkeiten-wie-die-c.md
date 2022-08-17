## Note
nid: 1627967550720
model: Basic-d7a3e
tags: 05_uebung, 05_uebung_rs, checklater, klausur
markdown: false

### Front
Nennen Sie zwei Möglichkeiten, wie die Cache-Kohärenz im Falle eines Mikroprozessorsystems mit einem Mikroprozessor und einem DMA-Controller sichergestellt werden kann.

### Back
<div>
<div><ul>
<li><strong>Möglichkeit 1</strong>:
 Der vom Prozessor und dem zusätzlichen Master (DMA Controller) 
gemeinsam benutzte Speicherbereich wird von der Speicherung im Cache 
ausgeschlossen.</li>
<li><strong>Möglichkeit 2</strong>:
 Cache-Clear oder Cache-Flush: Die Zugriffe von Prozessor und 
DMA-Controller auf den gemeinsamen Datenbereich werden von zwei 
unterschiedlichen Tasks ausgeführt; In diesem Fall kann der Task, die 
den DMA-Vorgang auslöst, dafür sorgen, dass der Cache gelöscht wird, d. h.  nachfolgende Prozessorzugriffe führen zu einem Neuladen des Caches.</li>
</ul>
</div></div>
