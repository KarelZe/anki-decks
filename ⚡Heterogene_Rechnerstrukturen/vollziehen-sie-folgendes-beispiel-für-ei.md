## Note
nid: 1611768898103
model: Basic-b122e
tags: 04_koheraenz, 11_para_block_prozess
markdown: false

### Front
Vollziehen Sie folgendes Beispiel für einen Write-Miss bei Tabellen-basierten Protokollen nach.

### Back
<div>Beispiel eines Write-Miss bei dem zwei Shared-Kopien in anderen Knoten enthalten sind.
</div><div>
</div><div>Block ist nicht in seinem physikalischen Speicher. Knoten schickt deshalb eine BusRdX-Nachricht (Anforderung) an Home-Knoten.</div><div>
</div><div>Home-Knoten sieht in Eintrag nach, blockiert ihn durch Setzen des Busy-Bits und sendet Invaldierungs-Nachrichten an beide Shared Kopien.</div><div>
</div><div>Invalidierungen werden dem Home  durch beide shared-Knoten bestätigt.</div><div>
</div><div>Der Home-Knoten schickt dann den Block an den Requester und setzt das Busybit.</div><div>
</div><div><img src="paste-ccf20e96783b608997f149d6fe6dad19c77542c3.jpg">
</div>
