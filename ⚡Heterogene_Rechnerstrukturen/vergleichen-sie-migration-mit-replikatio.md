## Note
nid: 1610823443687
model: Basic-b122e
tags: 04_koheraenz, 11_para_block_prozess
markdown: false

### Front
Vergleichen Sie <b>Migration</b> mit <b>Replikation</b>
hinsichtlich der <b>Cache-Koheränz</b>

### Back
<div><div><strong>Migration</strong></div><ul><li>Daten können zu einem lokalen Cache migrieren und dort in einer transparenten Weise verwendet werden</li><li>Reduziert die Latenz für einen Zugriff auf gemeinsames Datum, das auf einem entfernten Speicher liegt</li><li>Reduziert auch die erforderliche Bandbreite auf den gemeinsamen Speicher</li></ul><div><strong>Replikation</strong></div><ul><li>Gemeinsame Daten können als Kopien in lokalen Caches vorliegen, wenn etwa die Daten gleichzeitig gelesen werden</li><li>Reduziert die Latenz der Zugriffe und die Möglichkeit einer Blockierung beim Zugriff auf das gemeinsame Datum</li></ul></div>
