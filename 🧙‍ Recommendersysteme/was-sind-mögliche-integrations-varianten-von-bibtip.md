# Note
```
guid: jL=-By/!WB
notetype: Basic-b122e-20a86
```

### Tags
```
08_bib_tip
```

## Front
Was sind mögliche <b>Integrations-Varianten</b> von <b>BibTip</b>?

## Back
<ul>
<li><strong>Server Log Analyse / cgi-Skripte</strong>
<ul>
<li><b>User Observation Agent:</b> Auswertung von http-logs zur Abfrage von GET-Requests mit eingebetteter Session ID</li>
<li><b>Aggregation Agent:</b> Berechnet die Warenkörbe, schätzt die LSD-Verteilung, extrahiert Ausreiser mit inkrementellen, periodischen Updates.</li>
<li><b>Recommendation Agent:</b> CGI-script auf dem Recommendation Server generiert Empfehlungsseiten und wird über eingebettete Links im OPAC aufgerufen.</li>
<li>Hoher administrativer Aufwand!</li>
</ul>
</li>
<li><strong>Als Web-Service</strong>
<ul>
<li>Der Recommender Server ist ein (interner) Web Service</li>
<li>Verbindungsserver bietet ggf. ein Webservice-Interface an</li>
<li>Kunde hat volle Kontrolle über Layout, da nur die Informationen aus Webschnittstelle stammen</li>
</ul>
</li>
<li><strong>Mit JavaScript-Snippet</strong>
<ul>
<li>Integration von JavaScript Snippet in OPAC</li>
<li>Script für Kommunikationsprozess wird dynamisch neu geschrieben</li>
<li>geringer Integrationsaufwand, wenig anpassbar</li>
</ul>
</li></ul>
