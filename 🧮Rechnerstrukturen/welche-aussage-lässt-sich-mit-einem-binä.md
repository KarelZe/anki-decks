## Note
nid: 1621150712733
model: Basic-d7a3e
tags: 04_fehlertoleranz
markdown: false

### Front
Welche Aussage lässt sich mit einem <b>binären Fehlermodell</b> machen?

### Back
Binäre Fehlerzustandsfunktion \(Z\) gibt für jede Komponente und das System an, ob sie fehlerfrei sind (wahr = kein Fehler, falsch = Fehler):
\[Z:(S \cup\{S\}) \rightarrow\{\text { wahr, falsch }\}\]

Ein System, das nur dann fehlerfrei ist, wenn alle seine Komponenten fehlerfrei sind, wird charakterisiert durch
\[Z(S)=Z\left(K_{1}\right) \wedge \ldots \wedge Z\left(K_{n}\right)\]

Ein System, das nur dann fehlerfrei arbeitet, wenn es seit der Inbetriebnahme fehlerfrei war, erfüllt:
\[Z(S, t)=\wedge_{t_{0} \leq t} Z\left(S, t_{0}\right)\]
