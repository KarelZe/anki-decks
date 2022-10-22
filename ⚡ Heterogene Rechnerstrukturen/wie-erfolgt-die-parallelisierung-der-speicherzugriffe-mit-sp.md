# Note
```
guid: AP5E{eGE8c
notetype: Basic-d7a3e-4ce08
```

### Tags
```
12_Vektorverarbeitung
het_rs::07_vektorprozessoren
```

## Front
Wie erfolgt die Parallelisierung der Speicherzugriffe mit
Speicherverschränkung <i>(Memory Interleaving)</i>?

## Back
<div>
  <ul>
    <li>Ziel ist es min. 1 word pro Clock Cycle zu speichern.
    <li>Um die gewünschten Zugriffsraten zu erreichen, teilt man
    den Speicher in mehrere unabhängige Speicherbänke auf.
    <li>Speicher wird in \(n\) Speichermodule (oder Speicherbänke)
    \(M,\cdots,M_{n-1}\) aufgeteilt und jede Speicherbank mit einer
    eigenen Adressierlogik versehen.
    <li>Verteilung auf \(n\) Speicherbänke nennt man \(n\)-fache
    Verschränkung (<em>Interleaving</em>).
    <li>Speicherplatz \(A_i\) wird in der Speicherbank \(M_j\)
    gespeichert, g. d. w. \(j = i \mod n\).
    <li>Zuteilung
      <ul>
        <li>Adressen \(A_0, A_n, A_{2n},\cdots\) in Speicherbank
        \(M_0\)
        <li>Adressen \(A_1, A_{n+1}, A_{2n+1}, \cdots\) auf die
        Speicherbänke \(M_1\)
      </ul>
    <li>Bei \(n\)-facher Verschränkung werden nach einer gewissen
    Anlaufzeit in jedem Speicherzyklus \(n\) Speicherworte
    geliefert.
  </ul>
</div>
