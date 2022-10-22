# Note
```
guid: t%549P^xUv
notetype: Basic-9c783
```

### Tags
```
datenschutz::07_secure_multiparty
```

## Front
Was versteht man unter <b>Threshold Adversaries</b>? 🥷 In welchem Kontext ist es wichtig?  Welche Arten existieren?

## Back
Ein threshold adversary ist, dass ein Gegner einen Anteil der Knoten übernimmt z. B. \(t\) %.
Schwellwert t, Angreifer kann Set von
\(\left\{P_i, \ldots P_j\right\} \subseteq\left\{P_0, \ldots P_n\right\}\) Knoten mit
\(\left|\left\{P_{\mathrm{i}}, \ldots \mathrm{P}_{\mathrm{j}}\right\}\right| \leq \mathrm{t}\) übernehmen.

Drei typische <b>Thresholds</b>:
<ul><li>\(t<n / 2-\) Honest Majority, Mehrheit der Knoten ist ehrlich</li><li>\(51 \%\) - Angreifer korrumpiert die Mehrheit der Knoten im Protokoll</li><li>\(n-1\) - Angreifer kontrolliert alle Knoten bis auf einen ehrlichen</li></ul>
