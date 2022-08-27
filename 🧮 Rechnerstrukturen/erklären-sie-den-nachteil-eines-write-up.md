## Note
nid: 1628081341346
model: Basic-d7a3e-4ce08
tags: klausur
markdown: false

### Front
Erklären sie den Nachteil eines Write-Update Cache-Kohärenzprotokolls im Vergleich zu einem Write-Invalidate Protokoll.

### Back
Führt ein Prozessor bei einem Write-Update Protokoll mehrere Schreibzugriffe nacheinander auf das selbe Datum aus, muss dafür jeweils eine Broadcast-Operation durchgeführt werden, auch wenn die anderen Prozessoren das Datum nicht verwenden. Beim Write-Invalidate Protokoll muss das Datum in den anderen Caches nur einmal invalidiert werden und wird nur bei Bedarf neu geladen.
