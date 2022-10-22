# Note
```
guid: EQG`sJj*BP
notetype: Basic-d7a3e-4ce08
```

### Tags
```
derivate::02_forwards_futures
```

## Front
Wie ermittelt sich der <b>faire Terminpreis</b> für einen
<b>ertragsbringenden Basiswert</b> z. B. Aktie mit einem
<b>Arbitrage-Tableau</b>? (Variante mit Dividendenrendite
\(\delta\))

## Back
<table>
  <thead>
    <tr>
      <th>
      <th>\( t=0 \)
      <th>\(T=T\)
  <tbody>
    <tr>
      <td>Kauf Basiswert
      <td>
        <table>
          <tbody>
            <tr>
              <td>\( -S(0)e^{-\delta T}\)
        </table>
      <td>\(S(T)\)
    <tr>
      <td>Kreditaufnahme
      <td>\(S(0)e^{-\delta T}\)
      <td>\(S(0)e^{-\delta T} e^{rT}\)
    <tr>
      <td>PF
      <td>\(0\)
      <td>\(S(T)-S(0)e^{(r-\delta)T}\)
    <tr>
      <td>Forward long
      <td>\(0\)
      <td>\( S(T)-f(0,T)\)
</table>
<div>
  Mit No-Arbitrage-Argument folgt dann:
</div>
<div>
  \(f(0,T) = S(0)e^{(r-\delta)T}\)
</div>
