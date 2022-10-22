# Note
```
guid: rQ0L=`8$Uh
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::04_trees_rf
ultra
```

## Front
<p>Wie ist funktioniert <b>Randomization</b> bei <b>Random
Forests</b>?

## Back
<p style="letter-spacing: normal; text-indent: 0px; text-transform: 
 none; white-space: normal; word-spacing: 0px;"><span style= 
"font-weight: 400;"><strong>Baum-Ebene:</strong> Lasse einen
<em>forest</em> mit mehreren <em>trees</em> wachsen z. B.</span>
\(R = 500\)
<ul style="letter-spacing: normal; text-indent: 0px; 
 text-transform: none; white-space: normal; word-spacing: 0px;">
<li style="">Jeder Baum wird anhand eines <em style="font-weight: 
   400;">bootstrap samples</em> (Größe \(N\)) trainiert
</ul>
<p style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
<strong>Für jede Node:</strong>
<ul style="letter-spacing: normal; text-indent: 0px; 
 text-transform: none; white-space: normal; word-spacing: 0px;">
  <li style="">Wähle \(m\) Variablen zufällig aus aus allen \(M\)
  möglichen Variablen
  <li style="font-weight: 400;">Finde den besten Split für alle
  \(m\) Kriterien
</ul>
<p style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
Lasse die Bäume dann bis zur maximalen Tiefe wachsen
(Klassifikation) Votum / Durchschnitt der Bäume um Vorhersagen für
neue Daten zu erhalten.
