## Note
nid: 1613849612139
model: Basic-d7a3e-4ce08
tags: het_rs::09_programmierung
markdown: false

### Front
Wie erfolgt die <b>Interpolation</b> bei <b>HALadapt</b>?

### Back
<div>
  <div>
    <ul>
      <li>Für eine Interpretation werden zwei weitere Vektoren
      benötigt
        <ul>
          <li>Befindet sich gesuchte Problemgröße zwischen den
          Vektoren, ist Interpolation erlaubt
          <li>Ansonsten nur, falls Vektoren innerhalb eines
          Maximalabstands zur gesuchten Problemgröße liegen
        </ul>
      <li>Wertinterpolation erfolgt durch Erzeugung einer Geraden
      durch die zwei bisherigen Messpunkte
    </ul>
  </div>
</div>
