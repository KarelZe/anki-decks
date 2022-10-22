# Note
```
guid: tS>=gaz?bI
notetype: Basic-9c783
```

### Tags
```
datenschutz::04-internetprotokolle
```

## Front
Erklären Sie die <b>Arbeitsweise von Mixen</b>.

## Back
\(K\) öffentlicher Schüssel, \(R\) Zufallszeichenfolge zum
Auffüllen (zur Unterscheidbarkeit von identischen Nachrichten auf
Mixe) und \(A\) Adresse der nächsten Station <b>Arbeitsweise eines
Mix</b> Mix \(n\) erhält \(K_n\left(R_n, K_{n-1}\left(R_{n-1},
K_{n-2}\left(R_{n-2} \ldots\right.\right.\right.\)
Msg,\(\left.\left.\left.A_0\right), A_{n-2}\right),
A_{n-1}\right)\) mit \(K_n\) verschlüsselte Nachricht auspacken,
\(R_n\) löschen, Adresse \(A_{n-1}\) lesen sendet
\(K_{n-1}\left(R_{n-1}, K_{n-2}\left(R_{n-2} \ldots\right.\right.\)
Msg, \(\left.\left.A_0\right), A_{n-2}\right)\) an \(A_{n-1}\)
Letzter Mix sendet Msg unverschlüsselt an Adressaten \(A_0\) (kann
natürlich auch verschlüsselt erfolgen) <b>Visualisierung
Zwiebelprinzip:</b> <img src="paste-46c41a4158c992962f221add28aa1132dbdff4a8.jpg">
