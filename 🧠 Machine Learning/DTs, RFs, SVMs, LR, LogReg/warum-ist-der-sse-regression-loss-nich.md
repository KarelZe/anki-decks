## Note
nid: 1607431949287
model: Basic-d7a3e-4ce08
tags: ml::02_linear_classification
markdown: false

### Front
<p>Warum ist der <b>SSE</b> (regression loss) nicht als
Verlustfunktion für Lineare Klassifikation geeignet?

### Back
<p>
<ul style= 
"font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">
  <li>Man würde übersehen, dass \(y_i\) nur aus den Klassen
  \(\{0,1\}\) kommt.
  <li>Außerdem ist der regression loss nicht robust bei Ausreisern:
  <li><img src="126kztJPnHSRVJHmPTgW.png" style="width: 274px;">
</ul>
