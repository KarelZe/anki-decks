# Note
```
guid: K9syV6?l@v
notetype: Basic-d7a3e-4ce08
```

### Tags
```
derivate::02_forwards_futures
```

## Front
Wie ermittelt sich der Terminpreis bei einem <b>ertraglosen
Basiswert</b>?

## Back
<table>
  <thead>
    <tr>
      <th>
      <th>\(t=0\)
      <th>\(T=T\)
  <tbody>
    <tr>
      <td>Kauf Basiswert
      <td>\(-S(0)\)
      <td>\(S(T)\)
    <tr>
      <td>Kreditaufnahme
      <td>
        <table>
          <tbody>
            <tr>
              <td>\( +S(0)\)
        </table>
      <td>\(S(0)(1+r)^T\)
    <tr>
      <td>PF
      <td>\(0\)
      <td>\(S(T)-S(0)(1+r)^T\)
    <tr>
      <td>Forward long
      <td>\(0\)
      <td>\( S(T)-f(0,T)\)
</table>Aus No-Arbitrage folgt \(f(0,T) = S(0)(1+r)^T\)
