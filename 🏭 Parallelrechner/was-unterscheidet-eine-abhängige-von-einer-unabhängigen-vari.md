# Note
```
guid: kIP]vQB]=S
notetype: Basic-b122e-20a86
```

### Tags
```
4_3_4_4_entwurf_paralleler_programme
```

## Front
Was unterscheidet eine <b>abhängige</b> von einer <b>unabhängigen
Variable</b>?

## Back
<ul>
  <li>
    <p><strong>Unabhängig</strong>, falls eines der beiden
    Kriterien erfüllt ist
    <ul>
      <li>Variable wird in allen Iterationen der Schleife nur
      gelesen
      <li>Variable hat eine Array-Struktur und auf jedes
      Array-Element wird nur von einer Iteration der
      parallelisierten Schleife aus zugegriffen.
    </ul>
  <li>
    <p><strong>Abhängig</strong>, falls keines der o. g. Kriterien
    erfüllt ist. -Abhängige Variablen sind gemeinsame Variablen,
    die von mehreren Iterationen der parallelisierten Schleife
    uneingeschränkt gelesen oder geschrieben werden.
</ul>
