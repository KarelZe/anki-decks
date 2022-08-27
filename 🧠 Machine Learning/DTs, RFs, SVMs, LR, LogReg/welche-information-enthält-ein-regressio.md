## Note
nid: 1607185370732
model: Basic-d7a3e-4ce08
tags: ml::04_trees_rf
markdown: false

### Front
<p>Welche Information enthält ein <b>Regression Tree</b> und welche
ein <b>Classification Tree</b>?

### Back
<p style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
<strong>Regression</strong>
<ul style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
  <li>der prognostizierte Wert eines Knotens ist die
  <strong>durchschnittliche Antwortvariable</strong> für alle
  Beobachtungen im Knoten
</ul>
<p><img src="12oHRhRvhjDvvME2nhGB.png" style="width: 366px;">
<p style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
<strong>Klassifikation</strong>
<ul style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
  <li>die prognostizierte Klasse ist die <strong>häufigste
  Klasse</strong> einer Node (Mehrheitsvotum).
  <li>Man kann dadurch die erwartete Wahrscheinlichkeit für die
  Klassenzugehörigkeit erhalten.
</ul>
<div><img src="cart_classify_tree.JPG"></div>
