## Note
nid: 1605994938679
model: Basic-d7a3e
tags: 02_statistik, checklater
markdown: false

### Front
<p>Wie kann <b>Feature Selection</b> erfolgen?</p>

### Back
<p>Durch Domänen-Experte von Hand
<p>Mit automatischen Auswahlkriterien
<p>\(2^d\) mögliche Teilmengen von Attributen mittels Heuristiken
z. B. forward stepwise selection mit \(R^2\) bilden:
<div>
  <div>
    <ul>
      <li>Vorhersagekraft jedes Attributs für sich ermitteln;
      bestes Attribut behalten.
      <li>Schrittweise Auswahl von Attributen (Greedy): Bestes
      Attribut behalten oder Attribut behalten, das zusammen mit
      erstem beste Vorhersagen ermöglicht usw. (<i>forward stepwise
      selection</i>)
      <li>Schrittweise Eleminierung von Attributen : Jeweils das am
      wenigsten nützliche Attribut wird weggelassen (<i>backward
      stepwise selection</i>)
    </ul>
  </div>
</div>
