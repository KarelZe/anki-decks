# Note
```
guid: i80I:}i+Ce
notetype: Basic-d7a3e-4ce08
```

### Tags
```
derivate::02_forwards_futures
```

## Front
Wie lässt sich für einen ertragsbringenden Basiswert
<b>Long-Arbitrage</b> umsetzen? Wie <b>short-Arbitrage</b>?

## Back
<b>Long Arbitrage</b>:
<div>
  Annahme \(f(0,T) > S(0)e^{rT}\):
  <div>
    <table>
      <thead>
        <tr>
          <th>
          <th><span style="font-weight: normal;">in \(T\)</span>
      <tbody>
        <tr>
          <td>Forward short
          <td>\(f(0,T) - S(T)\)
        <tr>
          <td>Kreditfinanz. Kauf des Basiswerts
          <td>
            <table>
              <tbody>
                <tr>
                  <td>\(-S(0)e^{rT} + S(T)\)
            </table>
    </table>
  </div>
  <div>
    Damit folgt: \(f(0,T) - S(0)e^{rT}>0\)
  </div>
  <div>
    <b>Short Arbitrage</b>:
  </div>
  <div>
    Annahme \(f(0,T) < S(0)e^{rT}\):
  </div>
</div>
<table>
  <thead>
    <tr>
      <th>
      <th><span style="font-weight: normal;">in</span> \(T\)
  <tbody>
    <tr>
      <td>Forward long
      <td>\(S(T) -f(0,T)\)
    <tr>
      <td>Leerverkauf des Basiswerts + risikolose Anlage
      <td>
        <table>
          <tbody>
            <tr>
              <td>\(-S(T) + S(0)e^{rT}\)
        </table>
</table>Damit folgt: \(S(0)e^{rT} - f(0,T) > 0\)
