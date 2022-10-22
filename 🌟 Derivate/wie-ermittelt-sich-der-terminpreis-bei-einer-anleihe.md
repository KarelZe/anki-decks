# Note
```
guid: Lu,,gik9|`
notetype: Basic-d7a3e-4ce08
```

### Tags
```
derivate::02_forwards_futures
```

## Front
Wie ermittelt sich der <b>Terminpreis</b> bei einer <b>Anleihe</b>?

## Back
<table class="table table-striped table-bordered">
  <thead>
    <tr>
      <th>
      <th>\(t=0\)
      <th>\(T=T\)
  <tbody>
    <tr>
      <td>Kauf Anleihe
      <td>\(-S(0)\)
      <td>\(S(T)\)
    <tr>
      <td>Kreditaufnahme
      <td>\(+S(0)\)
      <td>\(S(0)(1+r)^T\)
    <tr>
      <td>PF
      <td>\( 0\)
      <td>
        <table>
          <tbody>
            <tr>
              <td>\( S(T)-S(0)(1+r)^T\)
        </table>
    <tr>
      <td>Forward long
      <td>\(0\)
      <td>
        <table>
          <tbody>
            <tr>
              <td>\( S(T)-f(0,T) + C_T\)
        </table>
</table>\(f(0,t) = S(0)(1+r)^T - C_T\)
<div>
  Basis = \(f(0,T) - K(0) = S(0)(1+r)^T - C_T - K(0) = (K(0) + C_0)
  (1+r)^T -C^T - K(0) =(K(0) + C_0) r T - (C_T - C_0)\)
</div>
<div>
  1. Term sind Haltekosten, zweiter Term Halteerträge.
</div>
